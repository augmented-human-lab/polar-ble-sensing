# Polar Verity Sense Projects Hub

This repository serves as a central hub for projects that utilize the Polar Verity Sense device for Heart Rate Variability (HRV) and Photoplethysmography (PPG) data streaming and saving.

## Project List

### 1. Polar-ble-python (by Hussel)

**Description:** This project features a `PolarDataHandler` class for processing and storing Polar sensor data, with a focus on PPG data.

**Key Features:**
- CSV file initialization with headers for PPG channels and timestamps
- Methods for handling various types of incoming data (control point responses, heart rate, PPG)
- PPG delta extraction, unpacking, and processing
- Data appending to CSV with corresponding timestamps

**Repository:** [https://github.com/augmented-human-lab/polar-ble-python](https://github.com/augmented-human-lab/polar-ble-python)

### 2. Polar Verity Streaming Interface (by Xiliu)

**Description:** This project provides code for streaming, processing, and visualizing data from the Polar Verity Sense device.

**Repository:** [https://github.com/cxiliu/polar-verity-streaming-interface](https://github.com/cxiliu/polar-verity-streaming-interface)

### 3. Polar BLE SDK Android App (by Prasanth)

**Description:** An Android application for streaming, processing, and visualizing data from the Polar Verity Sense device.

**Key Features:**
- Developed for the Floatation study
- Saves PPG data as CSV files in the device's data folder

**Repository:** [https://github.com/prasanthsasikumar/polar-ble-sdk](https://github.com/prasanthsasikumar/polar-ble-sdk)

## Contributing

If you have a project that uses the Polar Verity Sense device for HRV/PPG streaming or saving, please feel free to submit a pull request to add your project to this list.

## License

This repository is licensed under MIT. Please note that the individual projects linked here may have their own licenses.
