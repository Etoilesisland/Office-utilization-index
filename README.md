# Office-utilization-index
Use high-precision and real-time point location data to calcualte office utilization

# Indoor WiFi Location Data

This dataset contains indoor positioning data collected through WiFi signals in a multi-floor building environment. Each record represents a data point with information about location, time, and WiFi signal strength.

## Data Description

| Column Name       | Description                         |
|-------------------|-------------------------------------|
| `Index`           | Row index of the data               |
| `Building`        | Building identifier                 |
| `Latitude`        | Latitude coordinate of the point    |
| `Longitude`       | Longitude coordinate of the point   |
| `Floor`           | Floor where the data was collected  |
| `Time`            | Timestamp of the data collection    |
| `Conn_wifi_info`  | Connected WiFi (MAC & RSSI)         |
| `Indoor_wifi_info`| Nearby scanned WiFi (MAC & RSSI)    |

## Format

- **Time**: `YYYY-MM-DD HH:MM:SS`
- **WiFi Info**: `MAC_ADDRESS&-RSSI`
  - Example: `M00051180&-68`

## Sample Data
We have uploaded **typical data from three working days** . The data is provided in **GeoJSON** format. Each record represents a single WiFi scan point, including location, floor, timestamp, connected WiFi, and scanned nearby WiFi information.

