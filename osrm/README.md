# OSRM in Telenav    
We're going to research deeply in OSRM([Open Source Routing Machine](https://github.com/Project-OSRM/osrm-backend)). Here will be some study resources, experiences, etc.    

- [Getting Start with OSRM in Telenav](./doc/GettingStart.md)    
- [OSRM vs Valhalla](./doc/osrm-vs-valhalla.md)    

## Research from engine side
### Topics
- [OD In OSRM](./doc/od_in_osrm.md)
- [QueryHeap In OSRM](./doc/queryheap_in_osrm.md)
- [Understanding OSRM Graph Representation](./doc/understanding_osrm_graph_representation.md)    
- [Bidirectional Dijkstra In OSRM](./doc/bidirectional_dijkstra_in_osrm.md)     
- [OSRM Profile](./doc/osrm-profile.md)
- [OSRM Customization](./doc/osrm_customization.md)
- [OSRM Partition](./doc/osrm_partition.md)
- [OSRM Traffic Update](./doc/osrm_traffic_update.md)

### Graphs for source code
- [osrm-routed Startup Call Graph](./graph/osrm-routed_startup_callgraph.mmd.png)
- [osrm-routed Route Call Graph](./graph/osrm-routed_route_callgraph.mmd.png)
- [osrm-extract Startup and Process Call Graph](./graph/osrm-extract_startup_and_process_callgraph.mmd.png)
- [ViaRoutePlugin::HandleRequest Flow Chart](./graph/viaroute_handlerequest_flowchart.mmd.png)
- [TablePlugin::HandleRequest Flow Chart](./graph/table_handlerequest_flowchart.mmd.png)
- [BasePlugin::GetPhantomNodes(const datafacade::BaseDataFacade &facade, const api::BaseParameters &parameters) Flow Chart](./graph/BasePlugin_GetPhantomNodes_flowchart.mmd.png)
- [RoutingAlgorithms::ShortestPathSearch() Call Graph](./graph/routing_algorithms_shortestpathsearch_callgraph.mmd.png)    



## External links    
- [osrm-backend on Github](https://github.com/Project-OSRM/osrm-backend)
- [osrm-backend Wiki Home on Github](https://github.com/Project-OSRM/osrm-backend/wiki)
- [osrm Hosted Documentation](http://project-osrm.org/docs/v5.15.2/api)
- [osrm-routed HTTP API documentation](https://github.com/Project-OSRM/osrm-backend/blob/master/docs/http.md)
- [libosrm API Documentation](https://github.com/Project-OSRM/osrm-backend/blob/master/docs/libosrm.md)
- [Mapbox Blog Post: Robust navigation with smart nearest neighbor search](https://blog.mapbox.com/robust-navigation-with-smart-nearest-neighbor-search-dbc1f6218be8)
- [Course of University of Freiburg: Efficient Route Planning](https://ad-wiki.informatik.uni-freiburg.de/teaching/EfficientRoutePlanningSS2012)

