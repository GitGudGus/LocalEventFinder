# LocalEventFinder

## Table of Contents
1. [Overview](#Overview)
2. [Product Spec](#Product-Spec)
3. [Wireframes](#Wireframes)
4. [Schema](#Schema)

## Overview
### Description
A SwiftUI iOS app for discovering local events. Users can browse events fetched from JSON/API sources, search and filter by categories or dates, and save their favorite events for quick access. Features a clean, card-based interface design.

### App Evaluation
* **Category:** Lifestyle / Entertainment
* **Mobile:** Mobile-first iOS application. Takes advantage of location services and mobile-friendly browsing.
* **Story:** Helps users discover what's happening around them - concerts, festivals, workshops, and community events. Answers the question "What's Happening?" in their local area.
* **Market:** General audience - anyone looking to discover local events. Particularly useful for students, young professionals, and community members wanting to stay connected with local activities.
* **Habit:** Occasional to regular use - users check when planning their week or looking for weekend activities. Could become habitual for users who frequently attend events.
* **Scope:** Narrow to moderate scope. V1 focuses on event browsing, search/filtering, and favorites. Future versions could add user reviews, calendar integration, or social sharing.

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* User can view a list of local events
* User can search for events by name or keyword
* User can filter events by category (e.g., music, food, sports)
* User can filter events by date
* User can tap on an event to view full details
* User can favorite/unfavorite events
* User can view their saved favorite events

**Optional Nice-to-have Stories**

* User can share events with friends
* User can add events to their device calendar
* User can enable location services to see events nearest to them
* User can receive notifications for upcoming favorited events
* User can filter by distance/location
* User can see event details on a map view

### 2. Screen Archetypes

* **Events List Screen**
   * User can view all available local events
   * User can search events using search bar
   * User can access filter options
   
* **Event Detail Screen**
   * User can view full event information (date, time, location, description)
   * User can favorite/unfavorite the event
   
* **Favorites Screen**
   * User can view all their saved favorite events
   * User can remove events from favorites
   
* **Filter Screen** (Modal/Sheet)
   * User can select category filters
   * User can select date range filters
   * User can apply or clear filters

### 3. Navigation

**Tab Navigation (Tab to Screen)**

* Events (Home)
* Favorites

**Flow Navigation (Screen to Screen)**

* **Events List Screen**
   * Leads to Event Detail Screen (tap on event card)
   * Leads to Filter Screen (tap filter button)
   
* **Event Detail Screen**
   * Leads back to Events List Screen (back button)
   
* **Favorites Screen**
   * Leads to Event Detail Screen (tap on favorite event)
   
* **Filter Screen**
   * Returns to Events List Screen (after applying filters)

## Wireframes
[Add picture of your hand sketched wireframes in this section]

### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Schema 

### Models

**Event**
| Property | Type | Description |
|----------|------|-------------|
| id | String | Unique identifier for the event |
| title | String | Event name/title |
| description | String | Detailed event description |
| date | Date | Event date and time |
| location | String | Event venue/location name |
| address | String | Full address of the event |
| category | String | Event category (music, food, sports, etc.) |
| imageURL | String | URL to event image |
| isFavorite | Bool | Whether user has favorited this event (local) |

### Networking

**List of network requests by screen**

* **Events List Screen**
   * `(GET)` Fetch all events from API/JSON
     ```swift
     let url = URL(string: "API_ENDPOINT/events")
     // Fetch and decode JSON to [Event] array
     ```
   
* **Event Detail Screen**
   * `(GET)` Fetch individual event details (if needed)
     ```swift
     let url = URL(string: "API_ENDPOINT/events/\(eventId)")
     ```

**[OPTIONAL] Existing API Endpoints**
* Using static JSON file initially (can be replaced with live API later)
* Potential APIs for future integration:
  - Eventbrite API
  - Ticketmaster API
  - Meetup API

---
