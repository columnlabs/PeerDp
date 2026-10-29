# PeerDP

> PeerDP is not for everyday use.

PeerDP is a desktop streamer built using Node.js and Exotek's SimpleSockets, and it's just a proof of concept for now.
It is unencrypted and ANYONE on the same SimpleSocket channel can view your stream. It is public. If two clients are streaming on the same SimpleSocket channel, they will conflict and the output will be a flickering, back-and-forth stream of both clients.
