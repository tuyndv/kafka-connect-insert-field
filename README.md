InsertField with static field type

The following provides usage information for the Apache Kafka® SMT org.apache.kafka.connect.transforms.InsertField.

https://docs.confluent.io/platform/current/connect/transforms/insertfield.html

Properties:


Example on how to add to your connector:
```
"transforms": "InsertField",
"transforms.InsertField.type": "com.github.tuyndv.kafka.connect.smt.InsertField$Value",
"transforms.InsertField.static.field": "MessageTypeId",
"transforms.InsertField.static.type": "int32",
"transforms.InsertField.static.value": "1"

```
