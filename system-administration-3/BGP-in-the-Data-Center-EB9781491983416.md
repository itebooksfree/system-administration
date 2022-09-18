![Cover image for BGP in the Data Center](https://imgdetail.ebookreading.net/cover/cover/system_admin/EB9781491983416.jpg)

[BGP in the Data Center](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_1.html "BGP in the Data Center")
====================================================================================================================

Author : [Dinesh G. Dutt](https://ebookreading.net/search/author/Dinesh+G.+Dutt)

Release Date : 2017/08/01

ISBN : 9781491983416

Topic : [System Administration](https://ebookreading.net/search/category/system-administration)

Book Description
-----------------

 The Border Gateway Protocol (BGP) has emerged as the most popular routing protocol for the data center, yet many network operators and data center administrators are concerned about its complexity. This practical report peels away the mystique to reveal an elegant and mature, simple yet sophisticated protocol. Author Dinesh Dutt covers BGP operations, as well as enhancements that greatly simplify its use, so practitioners can refer to this report as an operational manual.
Because BGP’s origins lie in the service-provider world, few resources cover the protocol’s adaptation in the data center. This report meticulously covers the theory, design, and operationalization of BGP in data-center networks, including automation. You’ll learn how use innovations in BGP to simplify your network design, configuration, and management.
Specific configuration examples in this report are taken from the FRRouting open source routing suite, but the configuration should be quite familiar and easily translatable to other commercial and open source routing suites.
With this report, you’ll explore:
How the BGP theory of operations works for the modern datacenterEnhancements to BGP configuration provided by open networkingHow to automate datacenter deployment, including configuration and validationBCP best practices, including how to manage changes and troubleshoot routing problemsHow to set up BGP routing on the host        Show and hide more                
Table of Contents
-----------------

1. [Preface](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_4.html#_preface)
    1. [Software Used in This Book](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_4.html#software_used_in_th)
1. [1. Introduction to Data Center Networks](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_5.html#introduction_to_dat)
    1. [Requirements of a Data Center Network](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_5.html#requirements_of_a_d)
    1. [Clos Network Topology](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_5.html#clos_network_topolo)
        1. [Three-Tier Clos Networks](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_5.html#three-tier_clos_net)
        1. [Crucial Side Effects of Clos Networks](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_5.html#crucial_side_effect)
    1. [Network Architecture of Clos Networks](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_5.html#network_architectur)
    1. [Server Attach Models](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_5.html#server_attach_model)
    1. [Connectivity to the External World](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_5.html#connectivity_to_the)
    1. [Support for Multitenancy (or Cloud)](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_5.html#support_for_multite)
    1. [Operational Consequences of Modern Data Center Design](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_5.html#operational_consequ)
    1. [Choice of Routing Protocol](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_5.html#choice_of_routing_p)
1. [2. How BGP Has Been Adapted to the Data Center](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_6.html#how_bgp_has_been_ad)
    1. [How Many Routing Protocols?](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_6.html#how_many_routing_pr)
    1. [Internal BGP or External BGP](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_6.html#internal_bgp_or_ext)
    1. [ASN Numbering](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_6.html#asn_numbering)
        1. [Private ASNs](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_6.html#private_asns)
        1. [The Problems of Path Hunting](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_6.html#the_problems_of_pat)
        1. [ASN Numbering Model](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_6.html#asn_numbering_model)
    1. [Best Path Algorithm](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_6.html#best_path_algorithm)
    1. [Multipath Selection](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_6.html#multipath_selection)
    1. [Slow Convergence Due to Default Timers](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_6.html#slow_convergence_du)
        1. [Advertisement Interval](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_6.html#advertisement_inter)
        1. [Keepalive and Hold Timers](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_6.html#keepalive_and_hold_)
        1. [Connect Timer](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_6.html#connect_timer)
    1. [Default Configuration for the Data Center](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_6.html#default_configurati)
    1. [Summary](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_6.html#summary-id00005)
1. [3. Building an Automatable BGP Configuration](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_7.html#building_an_automat)
    1. [The Basics of Automating Configuration](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_7.html#the_basics_of_autom)
    1. [Sample Data Center Network](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_7.html#sample_datacenter_n)
    1. [The Difficulties in Automating Traditional BGP](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_7.html#the_difficulties_in)
    1. [Redistribute Routes](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_7.html#redistribute_routes)
    1. [Routing Policy](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_7.html#routing_policy)
        1. [Route-Maps](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_7.html#route-maps)
    1. [Using Interface Names as Neighbors](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_7.html#using_interface_nam)
    1. [Summary](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_7.html#summary-id00007)
1. [4. Reimagining BGP Configuration](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_8.html#reimagining_bgp_con)
    1. [The Need for Interface IP Addresses and remote-as](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_8.html#the_need_for_interf)
    1. [The Numbers on Numbered Interfaces](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_8.html#the_numbers_on_numb)
    1. [Unnumbered Interfaces](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_8.html#unnumbered_interfac)
    1. [BGP Unnumbered](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_8.html#bgp_unnumbered)
        1. [IPv6 Router Advertisement](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_8.html#ipv6_router_adverti)
        1. [RFC 5549](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_8.html#rfc_5549)
        1. [Forwarding with RFC 5549](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_8.html#forwarding_with_rfc)
        1. [BGP Capability to Negotiate RFC 5549 Use](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_8.html#bgp_capability_to_n)
        1. [Interoperability](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_8.html#interoperability)
    1. [A remote-as By Any Other Name](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_8.html#a_remote-as_by_any_)
    1. [Summary](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_8.html#summary-id00008)
1. [5. BGP Life Cycle Management](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_9.html#bgp_life_cycle_mana)
    1. [Useful show Commands](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_9.html#useful_show_command)
        1. [Displaying BGP Session Information](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_9.html#displaying_bgp_sess)
        1. [Displaying Routes Exchanged](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_9.html#displaying_routes_e)
    1. [Connecting to the Outside World](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_9.html#connecting_to_the_o)
    1. [Scheduling Node Maintenance](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_9.html#scheduling_node_mai)
    1. [Debugging BGP](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_9.html#debugging_bgp)
    1. [Summary](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_9.html#summary-id00009)
1. [6. BGP on the Host](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_10.html#bgp_on_the_host)
    1. [The Rise of Virtual Services](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_10.html#the_rise_of_virtual)
        1. [Anycast Addresses](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_10.html#anycast_addresses)
    1. [BGP Models for Peering with Servers](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_10.html#bgp_models_for_peer)
        1. [ASN Assignment](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_10.html#asn_assignment-id00)
        1. [Route Exchange Model](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_10.html#route_exchange_mode)
        1. [BGP Peering Schemes for Edge Servers](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_10.html#bgp_peering_schemes)
    1. [Routing Software for Hosts](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_10.html#routing_software_fo)
    1. [Summary](https://ebookreading.net/view/book/BGP+in+the+Data+Center-EB9781491983416_10.html#summary-id00010)
