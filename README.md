# aisp_coppeliasim_scenes


```txt
// This file defines all the continuous remote API server services (started at remote API plugin initialization, i.e. CoppeliaSim start-up)
//
// Each remote API server service requires following 3 entries:
//
// portIndex@_port = xxxx               // where xxxx is the desired port number (below 19997 are preferred for server services starting at CoppeliaSim start-up)
// portIndex@_debug = xxxx              // where xxxx is true or false
// portIndex@_syncSimTrigger = xxxx     // where xxxx is true or false. When true, then the service will be pre-enabled for synchronous operation.
//
// In above strings, @ can be any number starting with 1. If more than one server service is required, then numbers need to be consecutive and starting with 1
// Let's start a continuous remote API server service on port 19997:
portIndex1_port             = 19997
portIndex1_debug            = false
portIndex1_syncSimTrigger   = true
portIndex2_port             = 19998
portIndex2_debug            = false
portIndex2_syncSimTrigger   = true
portIndex3_port             = 20010
portIndex3_debug            = false
portIndex3_syncSimTrigger   = true
portIndex4_port             = 20011
portIndex4_debug            = false
portIndex4_syncSimTrigger   = true
portIndex5_port             = 20012
portIndex5_debug            = false
portIndex5_syncSimTrigger   = true
portIndex6_port             = 20013
portIndex6_debug            = false
portIndex6_syncSimTrigger   = true
portIndex7_port             = 20020
portIndex7_debug            = false
portIndex7_syncSimTrigger   = true
```
