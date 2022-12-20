
# Premier league fixtures

Project of visualization and analysis premier league matches in kibana.

Project contains getting fixtures from https://www.api-football.com/ by python script, send it to kafka topic and then by nifi export it from kafka to elasticsearch.

## Implementation

1. Clone the repository 

2. Run the Docker Compose:
```http
  docker-compose up -d
```
3. Open Jupyter Notebook:
```http
  jupyter nootebook
```
4. Create kafka topic in kafka

5. Open nifi web site in http://localhost:8443/nifi/

6. Upload nifi template

![App Screenshot](https://raw.githubusercontent.com/MOlowski/fixtures/master/media/nifi.png)

7. Start the project

8. Request fixtures in jupyter

9. Analyze data in kibana

![App Screenshot](https://raw.githubusercontent.com/MOlowski/fixtures/master/media/kibana_visualization.png)
