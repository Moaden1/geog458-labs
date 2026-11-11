## Project Explanation

### <b>1. Study Area and Dates<b>

#### Port of Seattle / Elliott Bay W/Coordinate Bounds: (-122.689, 47.376) to (-122.154, 47.776) During April 13, 2020 to April 15, 2020.

#### <p>I requested this specific region and date range to observe maritime traffic patterns in the early weeks of the COVID-19 pandemic’s stay-at-home orders. For context, Washington’s Governor at the time, Jay Inslee, issued a “stay home, stay healthy” order on March 23rd, 2020. I wanted to compare the movement of Cargo and Tanker vessels (as evidence of essential global supply chains) against the likely reduced patterns of Passenger vessels (such as halted cruise ships or reduced ferries) and Other vessels (recreational boating) during the lockdown.<p>
#### <p>To keep the dataset manageable and ensure smooth processing and playback, my data’s time period was limited to a strict 2-3 day window and drew a tight bounding box exclusively around the immediate Seattle port waters, bounded down to Des Moines and up towards Shoreline.<p>

### <b>2. Interpretation<b>

#### <p>Surprisingly enough, there were a lot of passenger vessels at the time, more than tanker and cargo vessels from a visual standpoint. I observed the passenger ships being most frequent between the hours of 9 am to 5 pm, with the flow of ships dying down around 8 pm and starting to pick back up around 7 a.m. The places these ships went/came from were Bainbridge Island, Bremerton, Vashon Island, Port Orchard, and a few others. For other vessel types, there was still some movement, and often time, it was much farther distances than passenger ships. This could be argued as evidence reflecting the necessity of maintaining global supply chains and essential goods movement despite the lockdown, but it also shows a reduced network of these (cargo, tanker) ships, which could alternatively suggest and explain hindrances to the movement of essential cargo in the global shipping industry at the time.<p>

### <b>3. Feature Proposal for a Potential User<b>

#### <p>This visualization can allow management officials and port logistics planners (or just for general future preparedness) to prepare for future disaster scenarios or strict lockdowns and help them better understand how stay-at-home orders affected the flow of vessels and identify what can be done about previous pitfalls. They need to analyze historical vessel flow to maintain optimal supply chain logistics and keep the economy stable during crises. After looking at deck.gl’s interactivity guide, I was interested in displaying a tooltip for a hovered object. Interactive Vessel Tooltips showing exactly what a vessel (non-passenger) is carrying exactly. When identifying ships that have been delayed, having a feature where users can hover above a delayed ship and receive instant data regarding what the ship is transporting (and possibly other data that may be useful, such as departure and destination locations).<p>