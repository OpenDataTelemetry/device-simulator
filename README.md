Set a jspn file fpr sunthetic data
Runb the simulator with the file as parameter
Verify integrity of JSON
Remove spaces from JSON

go run  --[CAN, LORA, JSON] --file=[PATH/TO/FILE]|message=[] --interval=[ms] \
        --[MQTT, KAFKA, POST, TCP, UDP] --host=[HOST] --port=[PORT] \
        --user=[] --password=[] 
        --topic=[]