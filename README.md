# AI-Powered-Travel-Planner-using-Multi-Agent-Systems
##  architecture
<p align="center">
  <img src="https://github.com/ldotmithu/Dataset/blob/main/ai_travel_agent_architecture.svg" width="600"/>
</p>


<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>AI Travel Agent - Agent Details</title>
</head>
<body style="margin: 0; padding: 0; background-color: #fff;">

<div style="font-family: Arial, sans-serif; padding: 20px; max-width: 1200px; margin: 0 auto;">
<h1 style="text-align: center; color: #333;">🤖 Agent Details & Specifications</h1>
<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(320px, 1fr)); gap: 20px; margin-top: 30px;">

<div style="border: 2px solid #999; border-radius: 8px; padding: 15px; background-color: #E1F5EE; box-shadow: 0 2px 8px rgba(0,0,0,0.1);">
<h2 style="margin: 0 0 10px 0; color: #333;">✈️ Flight Agent</h2>
<p style="margin: 5px 0; color: #666;"><strong>API:</strong> Skyscanner/Amadeus</p>
<p style="margin: 10px 0 5px 0; color: #333;"><strong>Tasks:</strong></p>
<ul style="margin: 5px 0; padding-left: 20px; color: #555;">
<li>• Search flights based on route & dates</li><li>• Fetch real-time prices</li><li>• Compare airlines & flight times</li><li>• Check availability</li>
</ul>
<p style="margin: 10px 0 5px 0; color: #333;"><strong>Output Format:</strong></p>
<code style="background-color: rgba(255,255,255,0.7); padding: 8px; border-radius: 4px; display: block; font-size: 12px; color: #333;">
flights: [{price, airline, duration, departure, arrival}]
</code>
</div>

<div style="border: 2px solid #999; border-radius: 8px; padding: 15px; background-color: #FAECE7; box-shadow: 0 2px 8px rgba(0,0,0,0.1);">
<h2 style="margin: 0 0 10px 0; color: #333;">🌤️ Weather Agent</h2>
<p style="margin: 5px 0; color: #666;"><strong>API:</strong> OpenWeatherMap</p>
<p style="margin: 10px 0 5px 0; color: #333;"><strong>Tasks:</strong></p>
<ul style="margin: 5px 0; padding-left: 20px; color: #555;">
<li>• Current weather at destination</li><li>• 5-day forecast</li><li>• Temperature & precipitation</li><li>• Weather alerts</li>
</ul>
<p style="margin: 10px 0 5px 0; color: #333;"><strong>Output Format:</strong></p>
<code style="background-color: rgba(255,255,255,0.7); padding: 8px; border-radius: 4px; display: block; font-size: 12px; color: #333;">
weather: [{temp, condition, forecast_5days, alerts}]
</code>
</div>

<div style="border: 2px solid #999; border-radius: 8px; padding: 15px; background-color: #FAEEDA; box-shadow: 0 2px 8px rgba(0,0,0,0.1);">
<h2 style="margin: 0 0 10px 0; color: #333;">🏨 Hotel Agent</h2>
<p style="margin: 5px 0; color: #666;"><strong>API:</strong> Booking.com</p>
<p style="margin: 10px 0 5px 0; color: #333;"><strong>Tasks:</strong></p>
<ul style="margin: 5px 0; padding-left: 20px; color: #555;">
<li>• Search available hotels</li><li>• Filter by budget & amenities</li><li>• Get pricing & ratings</li><li>• Check cancellation policy</li>
</ul>
<p style="margin: 10px 0 5px 0; color: #333;"><strong>Output Format:</strong></p>
<code style="background-color: rgba(255,255,255,0.7); padding: 8px; border-radius: 4px; display: block; font-size: 12px; color: #333;">
hotels: [{name, price, rating, location, amenities}]
</code>
</div>

<div style="border: 2px solid #999; border-radius: 8px; padding: 15px; background-color: #EAF3DE; box-shadow: 0 2px 8px rgba(0,0,0,0.1);">
<h2 style="margin: 0 0 10px 0; color: #333;">🎭 Attractions Agent</h2>
<p style="margin: 5px 0; color: #666;"><strong>API:</strong> Google Places</p>
<p style="margin: 10px 0 5px 0; color: #333;"><strong>Tasks:</strong></p>
<ul style="margin: 5px 0; padding-left: 20px; color: #555;">
<li>• Find POIs & attractions</li><li>• Create day-by-day itinerary</li><li>• Get opening hours & fees</li><li>• Calculate travel time</li>
</ul>
<p style="margin: 10px 0 5px 0; color: #333;"><strong>Output Format:</strong></p>
<code style="background-color: rgba(255,255,255,0.7); padding: 8px; border-radius: 4px; display: block; font-size: 12px; color: #333;">
attractions: [{name, type, hours, cost, location}]
</code>
</div>

<div style="border: 2px solid #999; border-radius: 8px; padding: 15px; background-color: #FBEAF0; box-shadow: 0 2px 8px rgba(0,0,0,0.1);">
<h2 style="margin: 0 0 10px 0; color: #333;">📋 Summary Agent</h2>
<p style="margin: 5px 0; color: #666;"><strong>API:</strong> News & Alerts</p>
<p style="margin: 10px 0 5px 0; color: #333;"><strong>Tasks:</strong></p>
<ul style="margin: 5px 0; padding-left: 20px; color: #555;">
<li>• Aggregate all data</li><li>• Calculate total cost</li><li>• Fetch travel alerts</li><li>• Get safety information</li>
</ul>
<p style="margin: 10px 0 5px 0; color: #333;"><strong>Output Format:</strong></p>
<code style="background-color: rgba(255,255,255,0.7); padding: 8px; border-radius: 4px; display: block; font-size: 12px; color: #333;">
summary: {total_cost, daily_breakdown, alerts, tips}
</code>
</div>

</div>
<div style="margin-top: 40px; padding: 20px; background-color: #f9f9f9; border-radius: 8px; border-left: 4px solid #534AB7;">
<h2 style="margin-top: 0; color: #333;">🔄 Data Flow Summary</h2>
<ol style="color: #555; line-height: 1.8;">
<li><strong>User Input:</strong> Provide destination, dates, budget, preferences</li>
<li><strong>Orchestration:</strong> LangGraph routes requests to all 5 agents simultaneously</li>
<li><strong>Parallel Execution:</strong> Each agent fetches data from its respective API</li>
<li><strong>Aggregation:</strong> LangChain consolidates all outputs into unified structure</li>
<li><strong>Formatting:</strong> Convert to JSON/Markdown with visual elements</li>
<li><strong>Output:</strong> Complete travel itinerary with all information</li>
</ol>
</div>
</div>

</body>
</html>
            
