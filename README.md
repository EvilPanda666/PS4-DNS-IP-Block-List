<p>I created an IP resolved gist from the original Sony PSN block list in numerical order 
	with the unresolved/dead hosts at the bottom. This is already an exhaustive list and 
	blocking one domain also blocks any others on the same subnet so I'm not sure it needs 
	to be expanded much more. I haven't had any issues with my PS4 connecting or downloading 
	updates with this list. Props to the folks who originally compiled this address list. 
	Feel free to merge or pull or anything else for that matter if it will help anyone. 
	Cheers.</p>

<code>
###########################ORIGINAL BLOCKLIST SOURCE#######################################
          https://github.com/phoanglong/ps4-dns-block/blob/main/ps4-block
###########################################################################################
Below is an IP resolved printout from the above link to a Sony/PSN block list in numerical 
order with unresolved/dead/downed hosts at the bottom. With this I'm able to simply IP 
range ban Sony PSN servers via my router/firewall. The ranges are not large by any means 
with many duplicate URL's. Hopefully this will save someone the pain of manually adding 
URL's to their DNS host provider or whichever method you use to block PSN for your HEN PS4.
###########################################################################################


###########################################################################################
                  IP Address Range	23.5.13.176/8 -- 23.212.62.85/8
###########################################################################################
hsa01.ps4.update.playstation.net                                            23.5.13.176
htw01.ps4.update.playstation.net                                            23.5.13.176
ps4-eb.ww.np.dl.playstation.net                                             23.42.201.128
crepo.ww.dl.playstation.net     (Resolves to: e3852.dscd.akamaiedge.net)    23.42.204.249 
urlconfig.api.playstation.com   (Resolves to: e259803.b.akamaiedge.net)     23.43.51.45                    
event.api.np.km.playstation.net                                             23.45.137.90
ps4updptl.uk.np.community.playstation.net                                   23.47.186.103
a01.cdn.update.playstation.org.edgesuite.net                                23.67.33.85
dbr01.ps4.update.playstation.net                                            23.67.33.85
duk01.ps4.update.playstation.net                                            23.67.33.85
dus01.ps4.update.playstation.net                                            23.67.33.85
al02.cdn.update.playstation.net                                             23.67.33.85
dcn01.ps4.update.playstation.net                                            23.67.33.95
fau01.ps4.update.playstation.net                                            23.198.125.219
fbr01.ps4.update.playstation.net                                            23.198.125.219
fcn01.ps4.update.playstation.net                                            23.198.125.219
feu01.ps4.update.playstation.net                                            23.198.125.219
heu01.ps4.update.playstation.net                                            23.198.125.219
hjp01.ps4.update.playstation.net                                            23.198.125.219
hkr01.ps4.update.playstation.net                                            23.198.125.219
hbr01.ps4.update.playstation.net                                            23.198.125.219
e4571.d.akamaiedge.net          (Resolves to: rnps-crl.dl.playstation.net)  23.203.211.186
fjp01.ps4.update.playstation.net                                            23.203.224.202
fkr01.ps4.update.playstation.net                                            23.203.224.202
fmx01.ps4.update.playstation.net                                            23.203.224.202
fru01.ps4.update.playstation.net                                            23.203.224.202
fsa01.ps4.update.playstation.net                                            23.203.224.202
ftw01.ps4.update.playstation.net                                            23.203.224.202
fuk01.ps4.update.playstation.net                                            23.203.224.202
fus01.ps4.update.playstation.net                                            23.203.224.202
hau01.ps4.update.playstation.net                                            23.203.224.202	
hcn01.ps4.update.playstation.net                                            23.203.224.202
hmx01.ps4.update.playstation.net                                            23.203.224.202
hru01.ps4.update.playstation.net                                            23.203.224.202
huk01.ps4.update.playstation.net                                            23.203.224.202
hus01.ps4.update.playstation.net                                            23.203.224.202
ps4updptl.eu.np.community.playstation.net                                   23.208.9.187
deu01.ps4.update.playstation.net                                            23.212.62.85
																			
###########################################################################################
                  IP Address Range	68.142.107.129/8 -- 69.28.162.0/8       
###########################################################################################
dkr01.ps4.update.playstation.net                                            68.142.107.129
dru01.ps4.update.playstation.net                                            68.142.107.129
dtw01.ps4.update.playstation.net                                            68.142.107.129
dau01.ps4.update.playstation.net                                            69.28.162.0
djp01.ps4.update.playstation.net                                            69.28.162.0
dsa01.ps4.update.playstation.net                                            69.28.162.0
dmx01.ps4.update.playstation.net                                            69.28.162.0
																			
																			
###########################################################################################
                IP Address Range	104.68.106.48/8 -- 104.114.76.192/8     
###########################################################################################
csla.np.community.playstation.net                                           104.68.106.48
post.net.playstation.net                                                    104.114.76.154
ps4-system.sec.np.dl.playstation.net                                        104.114.76.163
playstation.sony.akadns.net                                                 104.114.76.192
																			
																			
###########################################################################################
                 IP Address Range	184.28.98.75/8 -- 184.29.22.75/8        
###########################################################################################
get.net.playstation.net                                                     184.28.98.75
a192.d.akamai.net                                                           184.28.98.87
themis.dl.playstation.net                                                   184.28.148.17
static-resource.np.community.playstation.net                                184.28.148.227
e274.d.akamaiedge.net (fswitch.dl.playstation.net)                          184.29.20.18
asm.np.community.playstation.net                                            184.29.22.75
																			
																			
###########################################################################################
                 IP Address Range	208.111.152.8/8 -- 208.111.152.100/8    
###########################################################################################
tmdb.np.dl.playstation.net                                                  208.111.152.8
																			
																			
###########################################################################################
           Unresolved Hosts, temporarily offline or no longer exist         
###########################################################################################
apicdn-p014.ribob01.net                                                     Unresolved Host
api-p014.ribob01.net                                                        Unresolved Host
artcdnsecure.ribob01.net                                                    Unresolved Host
ps4updptl.jp.sp-int.community.playstation.net                               Unresolved Host
ps4.updptl.sp-int.community.playstation.net                                 Unresolved Host
sf.api.np.km.playstation.net                                                Unresolved Host
us.np.stun.playstation.net                                                  Unresolved Host
t-prof.np.community.playstation.net                                         Unresolved Host
dhk01.ps4.update.playstation.net                                            Unresolved Host
fhk01.ps4.update.playstation.net                                            Unresolved Host
hhk01.ps4.update.playstation.net                                            Unresolved Host


####################ORIGINAL BLOCKLIST SOURCE###########################
https://github.com/phoanglong/ps4-dns-block/blob/main/ps4-block
########################################################################
</code>
