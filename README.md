# Bitcoin e-waste estimate
Calculates a rough estimate of how much e-waste is generated per-transaction by the Bitcoin main network, based on the expected lifespan and hashrate of the ASIC Antminer S19J Pro.

## Results
Results while running at 18/10/2021

 * Hashrate = 143,388,851,802 GH/s
 * You'd need 1,433,888 S19J Pros to match the 143,388,851,802,000,000,000 H/s network hashrate
 * After 5 years of operation, 1,433,888 S19Js would have generated 20,934,764.8 kg of e-waste, 4,186,952.96 kg per year
 * Transactions in 24 hours = 268,899
 * The e-waste generated per transaction would be: 42.66g
 
## Some issues

 * Average ASICs in actual use have many different specs, making the used hash rate, weight and lifespan inaccurate
 * The actual number of yearly transactions is approximated by getting the number of transactions today and multiplying by 365, but the actual number of transactions varies a lot on different days.
 * Calculation could be wrong, no one checked except for me
