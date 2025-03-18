```markdown
# Kafka-Schema-Registry-Rest-Proxy

## Overview
This repository contains the Kafka Schema Registry REST Proxy, which provides a RESTful interface for managing and interacting with Kafka schemas.

## Prerequisites
- Java Development Kit (JDK) 8 or higher
- Apache Kafka
- Confluent Schema Registry

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/AshwinArch/Kafka-Schema-Registry-Rest-Proxy.git
   cd Kafka-Schema-Registry-Rest-Proxy
   ```

2. Build the project:
   ```bash
   ./gradlew build
   ```

## Usage
1. Start the Kafka Schema Registry REST Proxy:
   ```bash
   java -jar build/libs/kafka-schema-registry-rest-proxy.jar
   ```

2. Access the REST API at `http://localhost:8081` to interact with the Kafka schemas.

## Project Structure
- `src/` - Source code for the Kafka Schema Registry REST Proxy.
- `scripts/` - Shell scripts for managing the proxy.
- `build/` - Generated build files and artifacts.

## Contributing
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch
   ```
3. Make your changes.
4. Commit your changes:
   ```bash
   git commit -m "Description of your changes"
   ```
5. Push to the branch:
   ```bash
   git push origin feature-branch
   ```
6. Create a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For any questions or suggestions, feel free to open an issue or contact the repository owner.

```
