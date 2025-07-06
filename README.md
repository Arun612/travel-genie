# travel-genie
# 🧠 Agentic Travel Planner
Agentic Travel Planner An AI-powered travel planning assistant built with Microsoft AutoGen. It uses multiple collaborative agents to generate personalized itineraries, suggest destinations, estimate budgets.


An intelligent, multi-agent travel planning assistant built using [Microsoft AutoGen](https://github.com/microsoft/autogen) and powered by the Mistral-7B-Instruct model via OpenRouter. This system takes your travel preferences and collaboratively generates a personalized 5-day trip including:

- Day-wise itinerary
- Tourist attractions
- Budget accommodations
- Local transport suggestions
- Estimated total budget
- Final summarized plan

---

## 🚀 Features

- 🤝 **Multi-Agent Collaboration** via AutoGen
- 🧳 Personalized itinerary generation
- 🗺️ Attraction recommendations (scenic, cultural, offbeat)
- 🏨 Budget hotel suggestions (₹1000–₹2000)
- 🚍 Local transport planning with cost/time
- 💰 Budget estimation under ₹30,000
- 🧾 Final trip summary with clear formatting

---

## 🛠️ Agents

| Agent Name       | Role                                                                 |
|------------------|----------------------------------------------------------------------|
| `User`           | Initializes the travel query with preferences                        |
| `ItineraryAgent` | Creates a 5-day day-wise itinerary                                    |
| `PlaceAgent`     | Suggests top attractions per destination                              |
| `HotelAgent`     | Recommends budget hotels                                              |
| `TransportAgent` | Plans local travel modes, time, and cost                              |
| `BudgetAgent`    | Estimates total budget with breakdown                                 |
| `SummaryAgent`   | Combines all outputs into a final formatted travel plan               |

---

## 📦 Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
