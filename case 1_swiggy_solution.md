# Case 1 : Swiggy

## Solution to Swiggy's Mapping Business Outcomes to Product Outcomes: Swiggy's Challenge with Customer Support Queries

### About Swiggy 

Swiggy is a new-age consumer-first organization offering an easy-to-use convenience platform, accessible through a unified app founded by Sriharsha Majety,
Nandan Reddy and Rahul Jaimini in 2013. From this platform Swiggy provides it services to food delivery from restaurants, instant grocery from instamart, dine out facilities to eat out and Swiggy Scenes is an in-app feature on Swiggy that lets users discover, explore, and buy tickets for local live events, parties, DJ nights, live music, comedy shows, and workshops hosted at partner restaurants and venues.

### Swiggy's Mission

Swiggy's mission is to elevate the quality of life of the urban consumer by offering unparalleled convenience. Convenience is what makes them tick. It’s what makes them get out of bed and say, "Let’s do this".

### Swiggy's Vision

Swiggy's vision is to make people's life a little easier by elevating the quality of life for urban consumers with unparalleled convenience. They want to change how India lives, works and plays from its platform services through food delivery, instant grocery, dine out and swiggy scenes.

### Swiggy's Values

Swiggy's actions are strongly defined by the Swiggy values. Through ups, downs, and everything in between; Swiggsters put these values into practice in their everyday ways of working:

 1. By being humble, 
 2. Always be curious and learning,
 3. Being honest about displaying highest level of integrity.
 4. Consumer comes first,
 5. Display a founder mentality, 
 6. Think win-win,
 7. Think big,
 8. Stand-up & disagree but commit fully,
 9. Do more with less,
10. Move fast, break barriers and deliver results and 
11. Never settle.

### Swiggy's Challenge with Customer Support Queries

Swiggy has been facing a challenge with the increasing number of customer support queries. This has led to a backlog of queries and increased wait times for customers seeking assistance.

1. **Customer Support Queries from Food Delivery:** Swiggy's food delivery from restaurants is the famous services from the convenience platform and most of the customer support queries comes from this services asking questions about the food delivery, like:

   - Where is the ordered food? 
   - Why the food delivery person is late? 
   - Why any of the ordered food was missing from the ordered food?
   - Why food is taking time to prepare?
   - Why the quality of the food is low?
  
2. **Customer Support Queries from Instant Grocery:** Swiggy's second instant grocery from instamart is the next services from the convenience platform, where customer support queries about the instant groceries, like:

   - Why the instant grocery is taking time to deliver the grocery, if the services speaks as instant?
   - Why any of the grocery ordered from Instamart is not included after delivering it to the customer?
   - Why certain grocery item is not in the Instamart?
   - Why there is no quality in the grocery item?
   - Why there is no proper packaging of the grocery items?

 3. **Customer Support Queries from Eat Out:** Swiggy's third dine out facilities to eat out, is the third services from the convenience platform, where customer support queries about the eat out, like:

    - Customer faces issues like table booking confirmation.
    - Modifying or canceling bookings.
    - Restaurant refusal like not accepting table booking from a particular time.
    - Why swiggy dineout discount is not applied or not deducted from the final restaurant total?
    - Why there is a payment failure through a digital bill payment via the app at the restaurant counter?
 
 4. **Customer Support Queries from Swiggy Scenes:** Swiggy's fourth Swiggy Scenes is an in-app feature on Swiggy, is the fourth services from the convenience platform, where customer support queries about the swiggy scenes, like:

    - Customer faces issues about ticket booking & confirmation about event passes, QR codes, or confirmation details after payment.
    - Cancellations & refunds issues of a booked event ticket or questions about refund timelines if an event is changed or cancelled.
    - Queries regarding discount code (such as specific flash deals) which is failed to apply at checkout.
    - Questions about event details and venue access.
    - Queries about payment failures where money deducted from bank accounts about the event ticket booking was not successfully generated.

### Swiggy's Mapping Business Outcomes to Product Outcomes: Swiggy's Challenge with Customer Support Queries

1. **Swiggy's Business Objective:** 

     - Reduce the number of customer support queries.
     - Improve customer satisfaction.
     - Increase operational efficiency and reduce costs.
  
2. **Swiggy's Systems Thinking:** Swiggy approaches food delivery not merely as a logistical task, but as a dynamic, interconnected ecosystem. By applying systems thinking, Swiggy optimizes a complex, three-sided marketplace consisting of customers, restaurant partners, and delivery executives.

   Instead of viewing an order as an isolated transaction, Swiggy's architecture analyzes how every variable—from weather and kitchen prep times to user     preferences and fleet location—interacts in real-time.

   Here is a breakdown of how Swiggy applies systems thinking to its food delivery operations:

   1. **Controlling the End-to-End Loop:** When Swiggy launched in 2013, early competitors primarily functioned as restaurant discovery and menu aggregation platforms, leaving the actual delivery to the restaurants or  third-party logistics.

      - **The Systems Shift:** Swiggy realized that relying on external variables (like a restaurant's own delivery staff) broke the feedback loop and resulted in inconsistent customer experiences.
      - **The Solution:** They built and managed their own dedicated delivery fleet. By controlling the entire system—from the moment the order is placed to the moment it reaches the door—Swiggy could gather accurate data, control delivery times, and optimize the entire supply chain.

    2. **Entity Embeddings (The Connective Tissue):** To make the system "think," Swiggy converts all entities in its ecosystem—users, delivery partners, restaurants, and individual dishes—into mathematical vectors known as "embeddings".

       - This allows their Machine Learning models to easily measure similarities and relationships between seemingly disparate nodes.
       - For example, if a user searches for a specific dish that is unavailable in their area, the system understands the contextual similarity of the embeddings to suggest the closest alternative (e.g., suggesting Chicken Fried Rice if a specific Biryani is unavailable).

    3. **Asynchronous Logistics & Routing:** The physical movement of food is governed by algorithms that view the city as a living, breathing network.

       - **Time-to-Prep Integration:** The system doesn't just dispatch a driver immediately. It calculates the restaurant's historical preparation time for specific items. The delivery partner is assigned and routed so they arrive just as the food is ready, minimizing wait times at the restaurant and ensuring the food stays hot.
       - **Shared Fleet Optimization:** Rather than having completely siloed fleets for food delivery and grocery delivery, Swiggy utilizes a shared fleet. This systems-level optimization ensures that a driver dropping off a meal can seamlessly pivot to picking up a grocery order for Instamart or a package for Swiggy Genie, maximizing fleet utilization and reducing idle time.

    4. **DefraudNET: Holistic Fraud Detection** Swiggy's approach to handling refund requests perfectly illustrates systems thinking. Instead of just looking at the customer's claim in isolation, they built an AI framework called DefraudNET.

       - When a refund is requested, the system evaluates the entire ecosystem's state at that exact moment: the user's past behavior, the delivery partner's historical reliability, the restaurant's error rates, and even real-time environmental factors like heavy rain or traffic congestion.
       - By looking at the whole system rather than a single data point, Swiggy can accurately detect fraudulent claims while ensuring genuine customer grievances are resolved fairly.
      
    5. **Feedback Loops and Continuous Evolution:** Swiggy constantly adjusts its system based on macroeconomic and behavioral shifts.

       - **Quick Commerce Integration (Bolt):** Observing that the rise of 10-minute grocery delivery reshaped consumer expectations for all deliveries, Swiggy introduced "Bolt" to aggregate restaurants capable of ultra-fast preparation, bringing food delivery closer to quick-commerce speeds.
       - **Generative AI Integration:** Swiggy is embedding Gen-AI to analyze customer service interactions in real-time and provide democratized business intelligence directly to restaurant partners, helping them optimize their own internal systems based on Swiggy's macro-data.

3. **Swiggy's Business Outcomes vs Product Outcomes:**
