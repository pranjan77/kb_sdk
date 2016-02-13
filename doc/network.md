### <A NAME="network"></A>Network
https://narrative.kbase.us/functional-site/#/spec/type/KBaseNetworks.Network

```

   { ## KBaseNetworks.Network
     id:
     name:
     edges: [
              { id: 'Unique identifier of edge'                                         # e.g. "kb|g.3907.nds.10.edge.0"
                name:       'Name of edge'                                              # e.g. "Member of cluster"              
                node_id1:   'id of first node (source node for directed)'               # e.g. "kb|netnode.165"
                node_id2:   'id of second node(target node for directed)'               # e.g. "kb|netnode.1"
                directed:   'boolean false/true indicating directedness)'               # e.g. "false"
                confidence: 'Probability between 0 and 1 that interaction is true'      # e.g. 0
                strength:   'Value between 0 and 1 representing strength of interaction'# e.g. 0.8
                dataset_id: 'identifier of dataset that provided the edge information'  # e.g. "kb|g.3907.nds.10"
                properties: {"other_edge_property":1}                                   # e.g. {"color":"red"}
                user_annotations:{"user_annotation_1":1}                                # e.g. {"annotation":1}
              }
            ]
     nodes: [
              {
                entity_id: "id of entity represented by node"                           # e.g. "kb|g.3907.CDS.83425"
                id: "id of node"                                                        # e.g. "kb|netnode.7137"
                name:"string representation of node"                                    # e.g. "POPTR_0002s00410"
                properties: "Other properties of node"                                  # e.g. {}
                type: "type of node"                                                    # e.g. "GENE"
                user_annotations:"user annotations of node"                             # e.g. {}
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

