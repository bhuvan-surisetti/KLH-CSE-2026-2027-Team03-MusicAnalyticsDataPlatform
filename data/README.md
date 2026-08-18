# Data Source Reference & Schema Guidelines

## Overview
The `/data` folder contains telemetry log samples, synthetic telemetry generators, and schema documentation for the **Music Analytics Data Platform**.

## Data Privacy & Confidentiality Notice
> ⚠️ **IMPORTANT**: In accordance with project compliance rules, no raw confidential institutional data, proprietary licensed datasets, or API credentials/tokens should ever be committed to this directory.

## Telemetry Log Schema Reference
The platform processes streaming telemetry events with the following sample structure:

| Field Name | Type | Description |
|:---|:---|:---|
| `event_id` | String (UUID) | Unique identifier for the streaming event |
| `user_id` | String | Anonymized listener identifier |
| `track_id` | String | Unique identifier for the played song |
| `artist_id` | String | Unique identifier for the track artist |
| `timestamp` | Datetime (ISO-8601) | Event playback timestamp |
| `duration_played_sec` | Float | Total seconds listened |
| `track_length_sec` | Float | Full track duration in seconds |
| `completion_rate` | Float (0.0 - 1.0) | Calculated ratio of play duration to total track length |
| `skipped` | Boolean | Flag indicating if track was skipped before completion |
| `device_type` | String | Mobile, Desktop, Web, Smart Speaker |
| `country_code` | String (ISO-3166) | Geographic origin of the stream |

## External Data Source References
* **Million Song Dataset**: [http://millionsongdataset.com/](http://millionsongdataset.com/)
* **Spotify Web API Data Dumps**: Synthetic data generated based on standard Spotify Telemetry Specifications.
