Mobile App Dev - App Brainstorming 
===

## Favorite Existing Apps - List
1. Discord
1. Steam
1. inKind
1. Songkick
1. Reddit
1. Youtube Music
1. Google Tasks
1. Maps
1. ChatGPT
1. Shop

## Favorite Existing Apps - Categorize and Evaluate
### inKind
   - **Category:** Dining Out / Discounts 
   - **Mobile:** Fully leverages mobile hardware and context: location services (find nearby restaurants), Apple Pay integration, QR codes for payment, notifications for rewards or promos, and camera for receipt scanning. Excellent use of smartphone-native capabilities.
   - **Story:** “Dine out more, support local restaurants, and earn rewards while doing it.” It clearly benefits both sides — diners save money and discover great food, while restaurants get loyal customers and upfront cash flow.
   - **Market:** People already dine out; this simply makes it more rewarding. Target market includes foodies, urban professionals, and frequent diners.
   - **Habit:** Users interact regularly if they eat out often; push notifications for “rewards expiring soon” or “new restaurants nearby” help maintain engagement. Could add streaks or “restaurant milestones” to increase retention.
   - **Scope:** Building a full version requires APIs for payments, partner integrations, and restaurant data — but an MVP in Swift could focus on local discovery + digital wallet + QR redemption using mock data. Achievable if scoped carefully.
### Songkick
   - **Category:** Music / Live-Events Discovery. 
   - **Mobile:** Allows users to track their favourite artists, get notified when they announce tour dates in their area, view upcoming shows, buy tickets, and discover new concerts.
   - **Story:** Transform the way fans discover live music by linking their streaming accounts or music libraries, import artists, get alerts, and make sure they don’t miss concerts. The key value proposition: “Never miss another show.”
   - **Market:** The app serves fans who want to track artists and concerts worldwide. One stop shop to track and purchase tickets for your facorite artist.
   - **Habit:** The user checks for upcoming concerts, enables reminders, plans attendance with friends. Over time it becomes part of the “live music planning” behaviour. Example review: “track my favorite acts and shows in my immediate area … works as a great vacation-planning tool.”
   - **Scope:** Artist tracking & notifications, Show listings for cities globally,  Ticket-option linking (or buying), Music-library / streaming-service integrations.


## New App Ideas - List
1. Brain Overstimulation
    - Plays selected 'stimulating' videos in Picture-in-Picture (PiP) mode, allowing you to watch these videos while multi-tasking
3. Zero to Hero (Background Character Simulator)
    - Turn your life into a video game with side quests and achievements.
5. AutoAssist - Vehicle Monitor
    - An app for car owners to track maintenance, repairs, and gas expenses — includes reminders, cost analysis, and service history.
6. MindSwipe - Flashcard Learning
    - A minimalist learning app where users upload notes or PDFs, and the app automatically turns them into flashcards or “swipeable study cards.”
7. WorkFlowMe - Personal Automator
    - A app that helps users build small personal automations or “routines." For example, auto-texts, reminders, focus timers. Using Apple Shortcuts and APIs — but with a simpler interface.
9. Maximum Security Notes
    - Provides an extreme amount of authenticaiton layers for the notes
11. Local Event Finder
    - Simple app that lists local events (from a static JSON or API) with search, filtering and "favorites." 
8. Chess 2
    - Chess but you gain upgrades as you progress, allowing for new and creative gameplay.
14.  My Mini Monster
     - A digital pet that grows and reacts to user interaction. Player feeds it, play-mini games, and decorate its world.
16. Truth or Dare+ - Party Game for Friends
    - A modern spin on Truth or Dare with pre-loaded categories and a slick interface.
18. Voice Message Russian Roulette
    - Record voice messages that randomly play to your friends at unknown times.
20. Pocket Aquarium
    - A relaxing virtual aquarium where users collect, feed, and interact with fish.
22. SoundMap 
     - Song suggestion based on location. App takes your location and gives you a curated playlist for the region.
24. TuneIQ
    - AI song suggestion app based off moods and time of day as well as previous songs user has listened to.
26. Food Tracker AI
    - User will take photos of food. AI agent will find nutrition facts for food and give you the macros for the foods they're eating. User will also put in body goals and the app will recommend diets that user can follow.

## Top 3 New App Ideas
1. Local Event Finder
1. Auto Assist
1. My Mini Monster

## New App Ideas - Evaluate and Categorize

## 1. Local Event Finder ("What's Happening?")

**Description:** Simple app that lists local events (from a static JSON or API) with search, filtering, and "favorites."

**Evaluation:**
* **Category:** Lifestyle / Entertainment
* **Mobile:** Mobile-first iOS application. Takes advantage of location services and mobile-friendly browsing.
* **Story:** Helps users discover what's happening around them - concerts, festivals, workshops, and community events. Answers the question "What's Happening?" in their local area.
* **Market:** General audience - anyone looking to discover local events. Particularly useful for students, young professionals, and community members wanting to stay connected with local activities.
* **Habit:** Occasional to regular use - users check when planning their week or looking for weekend activities. Could become habitual for users who frequently attend events.
* **Scope:** Narrow to moderate scope. V1 focuses on event browsing, search/filtering, and favorites. Future versions could add user reviews, calendar integration, or social sharing.

---

## 2. AutoAssist - Vehicle Monitor

**Description:** An app for car owners to track maintenance, repairs, and gas expenses. Includes reminders, cost analysis, and service history.

**Evaluation:**
* **Category:** Productivity / Lifestyle
* **Mobile:** Mobile-first application. Benefits from push notifications for maintenance reminders and photo capture for receipts.
* **Story:** Helps car owners stay on top of vehicle maintenance and understand their automotive expenses. Answers "When is my next oil change?" and "How much am I spending on my car?"
* **Market:** Car owners, especially younger drivers or people managing multiple vehicles. Useful for budget-conscious users and those who want organized maintenance records.
* **Habit:** Moderate use - users log expenses after gas fill-ups or service appointments. Reminder notifications bring users back regularly.
* **Scope:** Moderate scope. Core features are data entry and tracking. Could expand to include mileage tracking, car value estimation, or integration with service providers.

---

## 3. My Mini Monster - Digital Pet

**Description:** A digital pet that grows and reacts to user interaction. Players feed it, play mini-games, and decorate its world.

**Evaluation:**
* **Category:** Entertainment / Games
* **Mobile:** Perfect for mobile. Benefits from notifications to remind users to check on their pet and quick session gameplay.
* **Story:** Brings back the nostalgia of Tamagotchi and virtual pets. Creates an emotional connection between user and their digital companion.
* **Market:** Broad appeal - children, teens, and adults who enjoy casual games or nostalgic experiences. Particularly popular with users who like cute, low-stakes gaming.
* **Habit:** Daily use app. Users check in regularly to feed, play with, and care for their pet. Notifications encourage habitual engagement.
* **Scope:** Moderate to broad. V1 includes basic pet care and simple interactions. Can expand with more mini-games, customization options, social features (visit friends' pets), or breeding mechanics.

---

## Comparison Summary

| Aspect | Local Event Finder | AutoAssist | My Mini Monster |
|--------|-------------------|------------|-----------------|
| **Complexity** | Low-Moderate | Moderate | Moderate-High |
| **Data Handling** | API/JSON parsing | Local persistence, CRUD | State management, animations |
| **UI Challenge** | List/detail views | Forms, charts | Animations, interactions |
| **Learning Value** | Networking, filtering | Data modeling, notifications | SwiftUI animations, game logic |
| **Team Suitability** | Good for beginners | Good balance | More ambitious |
| **Development Time** | 2-3 weeks | 3-4 weeks | 4-5 weeks |

All three are viable for your SwiftUI project! Local Event Finder is the most straightforward for learning fundamentals, AutoAssist provides good real-world app experience, and My Mini Monster is the most creative and engaging.

## Final App Chosen
We decided that we'll be creating a **Local Event Finder** app.
