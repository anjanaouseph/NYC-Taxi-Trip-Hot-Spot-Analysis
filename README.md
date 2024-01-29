# NYC-Taxi-Trip-Hot-Spot-Analysis

## Overview
This project conducts spatial hot spot analysis using Apache Spark to analyze NYC Taxi Trip datasets from 2009-2012. It includes two main tasks: Hot Zone Analysis and Hot Cell Analysis.

## Requirements
- Apache Spark
- Scala

## Data
- Point data: Pickup points from NYC Taxi trips.
- Zone data: For Hot Zone Analysis, located at `src/resources/zone-hotzone`.

## Tasks
1. **Hot Zone Analysis**: Calculates the hotness of rectangles by performing a range join operation between rectangle datasets and point datasets.
2. **Hot Cell Analysis**: Identifies significant spatial hot spots by calculating the Getis-Ord statistic on monthly taxi trip data.

## Contributing
Contributions are welcome. Please refer to the contributing guidelines for more information.

## License
This project is licensed under the MIT License.
