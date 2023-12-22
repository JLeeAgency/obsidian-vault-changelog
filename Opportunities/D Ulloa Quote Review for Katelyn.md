---
created: 2023-11-27T14:41
updated: 2023-11-27T14:41
---
Gable vs Hip roof, Citizens policy has Hip? Gable % is ~15%
	- I'm assuming they got those Wind Mit answers from a valid Wind Mit if those discounts are still in effect, which means the report also listed the roof as hip (though it's weird because the criteria is that gable roofing has to be less than 10% of total roof perimeter for a Wind Mit to claim hip type)
- 2321.34 Katelyn vs 3251 Citizens
- Credit Report not ran
- RCE modifications
	- You can put in approximate %s of hip vs gable roof. Sum up the perimeter (as best as you can) of the roof and find the % of it that's gable. Length of gable roof in ft / Total roof perimeter length.
	- Selecting Attached Garage, 2 Car tends to inflate the RCV vs using the exact sq ft. In this case there's two entries 'Finished Garage' and 'Finsihed Lower Garage' (the portion that's under the 2nd floor), you just sum them up and use that for 'Attached Garage, SF' 500 sq ft.
	- On RCE Tool We're missing:
		- FOP - FINISHED OPEN PORCH	416 sq ft
		- FSP - FINISHED SCREEN PORCH	129 sq ft
		- The AC system, this usually prepopulates correctly as 'Central Air Conditioning, Same Ducts'. Make sure not to remove this unless you know for sure they removed their AC.
		- Screen enclosure 800 sq ft
		- Changed home style from 2 story to colonial
		- Patio Brick and Tile 436 (most times the exact material isn't listed, pick the closest type; I used 'Patio, Tile')
		- Flooring corrected from what looks like default flooring type/values
			- ![[Pasted image 20231127135949.png]]
			- Property card says ceramic tile and carpet, 70% carpet and 30% is a rough guess based on normal homes
			  ![[Pasted image 20231127140053.png]]
- RCV changed from $497,905 to $533,401; They were likely heavily underinsured since I'm very sure the previous agency didn't go indepth. They were basically covering a Mercedes-Benz at the value of a Toyota.
	- You can pitch to them you can lower the RCV to be a closer match to the Citizens by removing home features if they *really* want to, but this value is more truthfully accurate to the homes current value, especially with today's inflation levels. 
- Added 'Hurricane Coverage Screened Enclosure' endorsement $10,000 under 'Optional Coverages'
	- Citizens policies don't cover screened enclosures; it's actually not offered on those policies. But if a hurricane happens a pool cage is one of the first things to go, so they should consider keeping it on, but we can remove it and it saves around $200.
	- Another reason why you want to do this instead of leaving it off... if they're shopping around quotes with other agencies, some other agent will offer it and tell them about the risk. Then the clients realize you didn't offer it.
- Filled in 'Flood Zone Details/Classification' under 'Basic/Additional Info', I didn't confirm if it was actually X because I'm short on time so you want to check Citizens PIWEST tool to see what Flood Zone they're in.
- Filled in purchase date and market value (these fields notoriously don't bridge over from EZLynx correctly)
- Plumbing material is usually going to be PCV or Copper. Copper is better but err on the side of safety and use PVC until you can verify via a 4 Point Inspection if they had one.
- Filled in previous address. Another one of those fields that don't transfer correctly.
- 'Order NCF Credit and Loss History' and confirm the disclosure to finalize quotes. If a claim pops up it could make the whole thing go sideways.
	- ![[Pasted image 20231127141618.png]]
- Quote bumps from ~$2630 to $2968 after consumer report ran.
- Central Monitoring Station was selected for 'Central Fire Alarm'
	- Just to be clear, this is if their home has 24/7 3rd party monitoring for fires, like ADT. They have to provide an invoice or contract agreement to prove this. I left it on but if you aren't sure about this, remove it.
- Secured Community Discount, changed to 'Single entry leads to subdivision' because she does live in a subdivision:
	- ![[Pasted image 20231127142013.png]]
	- It's not gated, but it does have limited access
	- We can increase Personal Liability from $100k (which is the only option on Citizens policies) to $300k with private-market carriers. This would be a wise move for them considering how everyone loves to take people to court and the cost for 3x liability coverage is $15/yr

**Biggest takeaway here: The original Citizens policy very likely is heavily underinsuring their home. We could remove some home features, and for example shaved it down from $533k to ~$460k, would reduce the premium from $2870 to $2592. So maybe around $2300 if matching exactly their old coverage, but that's not our recommendation** (Also assumes the central fire alarm discount is valid)