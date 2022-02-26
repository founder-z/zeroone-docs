# Backend workflow

Back-end workflows allow you to connect your apps using a variety of APIs to share and manipulate data without code. It allows to move and transform data between different apps and databases without getting caught up in API docs and troubleshooting CORS errors.

The current backend workflow uses a workflow automation tool for services called n8n, refer to [n8n documentation](https://docs.n8n.io) for more details



Current default n8n is run with folliwing configuration:

| Name                                         | Value                         |   |
| -------------------------------------------- | ----------------------------- | - |
| NODES\_EXCLUDE                               | n8n-nodes-base.executeCommand |   |
| EXECUTIONS\_PROCESS                          | main                          |   |
| N8N\_SKIP\_WEBHOOK\_DEREGISTRATION\_SHUTDOWN | "true"                        |   |
