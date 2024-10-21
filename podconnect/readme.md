kubectl exec -it pod2 -n n1  -- /bin/bash

## then try wherther you can access service of pod1
curl pod1-service

