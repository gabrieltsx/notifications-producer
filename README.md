## Notifications Producer

Simple Kafka producer project

## Usage

First, execute the project: https://github.com/gabrieltsx/notifications-service, and configure kafka server credentials:

`const kafka = new Kafka({
    clientId: 'kafka-producer',
    brokers: ['national-oriole-7390-us1-kafka.upstash.io:9092'],
    sasl: {
      mechanism: 'scram-sha-256',
      username:
        'bmF0aW9uYWwtb3Jpb2xlLTczOTAkbtj8Bi95OqL_ww2zIXAI0MsJkzWvkKoNNDs',
      password:
        '*****',
    },
    ssl: true,
})
`
## Contact

Any question, bug and comment, you can mail me in gabrielhenrique.ls96@gmail.com or use Issues tab here in GitHub

Thank you.
