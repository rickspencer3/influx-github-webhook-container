```
version: "3.7"

services:
  telegraf:
    image: 
    environment:
      - PORT=
      - ENDPOINT=
      - INFLUX_URL=https://us-west-2-1.aws.cloud2.influxdata.com
      - INFLUX_TOKEN=
      - INFLUX_ORG=
      - INFLUX_BUCKET=
    command: telegraf --debug
```