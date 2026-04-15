RTT vs Speed-of-Light Analysis



1\. Highest Inefficiency



The highest inefficiency ratio was observed for Sendai, with a ratio of approximately 14.90. According to the Submarine Cable Map, Sendai is connected via the Japan Information Highway, a domestic fiber-optic network that links to major submarine cable landing points in Chikura. From there, traffic crosses the Pacific Ocean via cables such as Unity to reach the western United States, then crosses the country to get to Boston. 

This means that packets do not travel directly to Sendai, but instead follow an indirect route through Chikura before reaching the final destination. This additional routing, combined with shared submarine cable infrastructure and a university server at the endpoint, significantly increases the total RTT, resulting in a very high inefficiency ratio.



This is likely due to indirect routing paths, congestion, and the use of university servers that are not optimized for low-latency global access. In many cases, packets must travel through multiple intermediate networks and major hubs before reaching their destination, significantly increasing the total RTT.



2\. Closest to Theoretical Minimum



The cities closest to the theoretical minimum RTT were Mumbai (ratio 1.12) and Tokyo (ratio 1.17). These values indicate relatively efficient routing paths.



This suggests that these regions have strong connectivity to global backbone networks and more direct fiber routes, allowing data to travel along paths that more closely match the great-circle distance.



3\. Why Africa Routes Through Europe



Traffic to Lagos often routes through Europe due to the structure of global internet infrastructure. Many submarine cables connecting Africa are linked to European hubs such as London and Lisbon, and there are fewer direct connections between African countries and other regions.



As a result, data traveling to or from Africa frequently passes through Europe first, increasing latency and inefficiency. Improving regional fiber networks and increasing the number of direct connections and Internet Exchange Points within Africa would help reduce this inefficiency.



