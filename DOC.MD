Emulation features an ethical approach to various exploits with the goal of emulating 1:1 server<->client interaction with no ghosting or desyncing.

Manipulated packets are hooked at order < -10 > for client and < undefined behavior > for server.
Any - client - skill related packets can be hooked at "order : -11" or lower to retrieve information
Any - client - skill related packets can be hooked at "order : -9" or higher to modify them ( not recommended )
Any location related packets can be hooked at "order : -101" or lower to modify them for personal needs ( not recommended, likely to result in a ban )
Any location related packets can be hooked at "order : -99" or higher to retrieve information