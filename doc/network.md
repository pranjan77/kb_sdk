### <A NAME="network"></A>Network
https://narrative.kbase.us/functional-site/#/spec/type/KBaseNetworks.Network

```

   { ## KBaseNetworks.Network
     id:
     name:
     edges: [
              { id: 'Unique identifier of edge'                                   # e.g. "kb|g.3907.nds.10.edge.0"
                name:       'Name of edge'                                        # e.g. "Member of cluster"              
                node_id1:   'id of first node (source node for directed)'         # e.g. "kb|netnode.165"
                node_id2:   'id of second node(target node for directed)'         # e.g. "kb|netnode.1"
                directed:   'boolean false/true indicating directedness)'         # e.g. "false"
                confidence: 'Probability between 0 and 1 that interaction is true' # e.g. 0
                strength:   'Value between 0 and 1 representing strength of interaction' # e.g. 0.8
                dataset_id: 'identifier of dataset that provided the edge information'   #"kb|g.3907.nds.10"
                properties: 
                user_annotations:
              }
            ]
     nodes: [
              { id:
                name:
                entity_id:
                type:
                properties:
                user_annotations:
              }
            ]
     datasets: [
                 { id:
                   name:
                   description:
                   network_type:
                   source_ref:
                   taxons:
                   properties:
                 }
               ]
     properties:
     user_annotations:

