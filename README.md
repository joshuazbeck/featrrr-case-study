## Case Study: Featrrr – From Fragmented Code to App Store Success

I was brought onto **Buddiebooking Inc.'s** Featrrr project when the app was still in a challenging state. **Featrrr** is a platform that connects influencers with advertisers, giving influencers a place to sell their services and collaborate with sponsors. The app includes key features like **dynamic messaging**, **payment management**, **anonymous user login**, and **push notifications**—all designed to make influencer-sponsor relationships smoother and more efficient.

When I joined the team, Featrrr's codebase was scattered and inconsistent. Over the past year, it had passed through multiple developers and teams, resulting in a project that lacked structure and direction. Initially, my job was to integrate audio chat into the app. However, it quickly expanded into a larger role, where I took responsibility for redesigning the app, refactoring the code, and making sure Featrrr was ready for a successful launch on the App Store.

[Live App on the App Store](https://apps.apple.com/us/app/featrrr/id6476980982)

### Client Review of Services

>I don’t know where to start when it comes to Josh, so let’s start by saying he’s a good human being first. He was able to connect with me and in turn my idea, he fully grasped the concept, communicated and adhered to discussed deadlines. I never wondered where he was or if there would be bad news I felt safe working with Josh because he proved to be so capable. Everything I could imagine he brought to life better than I originally thought, he took care of edge cases and kept me informed even with my limited knowledge of coding made it understandable. All the way to the App Store, his experience and expertise in iOS development allowed him to see and develop for the bigger picture. His honesty and forthcomingness never left me anxious he does what he says he can do and in the estimated time he says he can do it or will communicate otherwise. ...[H]e gave me faith in the freelancers realm, Thanks Josh.
### Technical Stack

Featrrr was built using a modern, scalable technical stack:

- **Front-End**: SwiftUI – used to create a responsive and intuitive user interface.
- **Backend**: Firestore NoSQL – a cloud-based database that handles user data efficiently.
- **Backend Functions**: Firebase Functions (using Node.js) – for handling server-side logic and automation.
- **Payment System**: Stripe API – to enable secure payments between users and advertisers.

---

### Chat Messaging

The chat messaging system was a key part of Featrrr. I integrated **audio messaging**, allowing users to communicate more efficiently. I also added the ability to send **multiple photos** at once and developed a **custom photo gallery** component for easy browsing. This, combined with **link sharing**, created a dynamic and flexible messaging platform. Extensive error handling and cleanup made sure that the user experience was smooth, regardless of the message type or content.

### Push Notifications

Push notifications play an important role in keeping users engaged with Featrrr. I implemented a system that sends **payment-related notifications** using Firebase Messaging. This not only kept users updated on important transactions but also allowed us to integrate **deep linking**, making sure users could tap on notifications and be taken directly to the relevant screen within the app. This was critical for maintaining a seamless user experience.

### Deep Linking

Deep linking was essential for improving user navigation within the app. With deep linking enabled, users could click on a notification or shared link and be taken directly to a specific section or page in the app, skipping unnecessary steps. This was particularly useful for **payment notifications** and other time-sensitive information, allowing users to quickly access relevant areas of the app without manually searching for them.

### Anonymous Users

To enhance privacy and security, I added functionality for **anonymous user login**. This allowed users to interact with the app without revealing personal details, making the platform more inclusive and secure. I also expanded the use cases for anonymous users, ensuring that they had access to the same features while maintaining a safe, restricted environment that protected both influencers and advertisers from misuse.

### UI Redesign

Featrrr needed a major overhaul in terms of design. I led a complete redesign of the app's **user interface (UI)**, transforming it from a basic, outdated look into a polished and modern experience. I also reimagined the app’s **icon and branding** to ensure it was cohesive and visually appealing, providing a fresh, unified look across the platform.

### Code Refactoring

The app’s code was a mix of different development styles from past teams. I refactored the entire codebase, applying best practices to follow a **ViewModel (VM) architecture** for SwiftUI. This approach made the app more stable, scalable, and easier to maintain. Refactoring was crucial for improving performance and preparing the app for long-term updates and new features.

---

### Publishing on the App Store

In addition to development, I guided the team through the **App Store Optimization (ASO)** process, including keyword selection, legal compliance, and best practices for submission. This ensured that Featrrr was not only approved but also positioned to reach a larger audience. The App Store approval process went smoothly, and the app was successfully launched without major issues. After the launch, I continued to provide support with bug fixes and improvements to move the app toward a stable release.

---

### Conclusion
This project was a rewarding challenge, taking an app that was struggling to get off the ground and turning it into a fully realized platform. Featrrr’s successful launch on the App Store marked a significant milestone for Buddiebooking Inc., and it was exciting to play a key role in that transformation.
