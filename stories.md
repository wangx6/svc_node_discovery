Setup
- create empty database
- clone database
- bind the database cluster to a environment (dev, qa, prod, others)
- create orchastrator (load balance, health check)


Release
- create release bucket
- jenkins


Test



Monitor



Dev
as a ms
i want to use my registary cache 
so that i can make sure i am available

as a ms
i want to poll the discovery service 
so that i can make sure i have the most uptodate registary

as a ms
i want to persist the registary i polled from the discover service
so that i can use it when i reboot and the discovery service is not available

as a ms
i want to submit my new location to the discover service
so that i can make sure my details can be shared

as a ms
i want to read from the persisted registary when neither the discovery and the my cache is not available

as a DS
i want to have at least 3 instance running
so that i can maximize my availability

as a DS
i want to have my ip to be static
so that i can maximize my availability
