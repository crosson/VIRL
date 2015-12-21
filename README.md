# VIRL
Various topologies


Leaf Spine Vxlan topology    
Basic p2p L3 underlay between Leaf and Spine. Spine's are basic iosv routers. Leave's are CSR100v since they are the only virtual platform that supports acting as the VTEP. I extend SVI's down to the TOR routers but in an ideal world that would be collapsed back into the leaf.