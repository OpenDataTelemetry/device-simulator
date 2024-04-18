Set a jspn file fpr sunthetic data
Runb the simulator with the file as parameter
Verify integrity of JSON
Remove spaces from JSON

go run mqtt 
go run kafka 
go run http-post
go run tcp
go run udp
go run grpc
go run ws

--[can, lora, json] *REQUIRED*
--file=[PATH/TO/FILE] OR message=[] 
 --host=[HOST] --port=[PORT] *REQUIRED*

--interval=[ms] //No interval, just once

       
        --user=[] --password=[] 
        --topic=[]