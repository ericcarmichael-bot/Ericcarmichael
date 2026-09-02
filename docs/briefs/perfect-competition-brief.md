## Case info

The farm is attempting to optimize the crops in the planter beds in order to maximize profit and ensure that marginal costs are not exceeded. 
The farm is too small in this example to influence market prices. They are a price taker. 
The question that the farm is trying to answer is what particular crops and in what quantities it should plant in the available space: 64 total beds. 16 beds by 4 plots.
This is a small farm with a single set of hands and four temporary workers.
The only variable that the farm can control is what crops go into the ground.
Every additional bed of crop that is planted increases the labor required and makes each bed incrementally more expensive due to pest pressures, harvest bottlenecks, walking time, etc
The season is 36 weeks long. 
Fixed costs are 20,000
There are 64 beds in total. 16 beds by 4 plots. 
The farmer has a cost of 50,000 per season with half her time in the fields (assuming 720 hours of work), and additional labor is provided by 4 temporary workers at $25,000 each, 1,440 hours each at $17.36 an hour.
Diminishing Crop, Max beds, Price $/bed, Labor hrs/wk/bed, Fertilizer $/bed, returns
Tomatoes 20, $8,800, 2.50, $880, 10.00% / bed
Carrots 20, $2,094, 0.833, $440, 2.50% / bed
Mesclun 30,  $2,700, 1.25, $880, 1.25% / bed
The season is planted a single time. There is no mid-season reallocation if the mix is incorrect. Any error here isn't an inefficiency; it's locked in for the 36-week season, which means a bad crop mix will carry the labor and fertilizer costs through the season

## Hypothesis

I hypothesize that we need the following assortment of crops:
-Tomatoes have the highest revenue but also the highest diminishing returns and the most labor hours. Therefore, tomatoes will be very attractive initially, but their margin will decline quickly. I hypothesize that we will need 8 beds of tomatoes rather than the full 20 due to diminishing returns
-Carrots have the lowest labor costs and fertilizer costs and low diminishing returns of 2.5%. Because this uses the resources more efficiently, I suspect we would maximize this crop to 20 beds
-Mesclun has the lowest diminishing returns so this will likely take up the rest of the slack. I expect Mesclun would become increasingly attractive as the tomatoes' return declines. I suspect we would maximize this crop as well and plant 30 beds. 
-This means that I hypothesize a total of 58 beds planted. 

## How I would know I was wrong

- I claim that tomatoes are the first crop to become unattractive and only 8 of the 20 possible beds should be planted. If the model outputs that I need fewer or additional beds of tomatoes, my read on how the diminishing returns work would be incorrect.
- I claim that carrots use the available resources efficiently enough to run up to the bed cap of 20. If the model returns fewer than 20 beds, something is constraining the carrots that I did not account for.
- I claim that mesclun also runs up to its bed cap of 30 due to its more efficient use of resources. If the model returns fewer than 30 beds, something is also constraining the mesclun that I have not accounted for.
- If the total beds planted are more than 58 beds, I will also be proven incorrect.
