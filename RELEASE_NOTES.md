
quiche-mallard/0.21.1
- 2025-06-04 Mark fork as deprecated now that patches are upstream

quiche-mallard/0.21.0
- 2025-01-13 Bypass static_mut_refs lint
- 2025-01-13 Add fork description to README
- 2025-01-10 Reconfigure GitHub features for fork
- 2025-01-10 Rename quiche crate to quiche-mallard
- 2025-01-10 Setup fork for publishing with cargo-release
- 2024-06-11 h3: if readable after Finished, call recv again
- 2023-11-30 Allow prefix
- 2023-11-22 Add zero copy send methods.
- 2023-01-26 Add the ability to provide a custom BufFactory to a quiche connection
- 2024-06-05 Properly track datagrams in for BBRv2 bandwidth
- 2024-06-03 Use InflightReduction for bw_lo_mode in BBRv2
- 2024-06-03 report number of bytes acked in stats
- 2024-05-15 Avoid having minrtt at Duration::max
- 2024-03-21 Use nanosecond precision for Bandwidth
- 2024-03-12 Replace congestion control implementations with google/quiche congestion control implementations
- 2024-03-11 Move reusable acks vec into Recovery
- 2024-03-08 Move congestion into module
- 2024-03-08 Move all congestion control related fields to a new struct
- 2024-03-07 Move detect acked packets logic to epoch
- 2024-03-01 Rewrite drain_packets
- 2024-03-01 Rewrite RttStats
- 2024-03-01 Implement the loss detection timer as a struct
- 2024-03-01 Merge epoch data into a struct
- 2024-02-28 Count bytes_in_flight outside congestion model
- 2023-12-18 Move RTT related stats and op to a separate struct


