
# Project Title

Addition to Traffic Light Management Systems for Faster and Safer Passage of Emergency Vehicles

## Summary

An enhancement to traffic management systems specifically for traffic lights, aimed at optimizing the passage of emergency vehicles (ambulances, fire trucks, police cars) in a faster and safer manner.

## Background

It is critical for emergency vehicles to reach their destinations as quickly and safely as possible. Existing systems, such as AI4UTC developed by the Huddersfield University, contribute significantly to achieving these goals. These systems generally rely on identifying emergency vehicles and giving them priority at intersections. However, their accuracy is not always optimal. My proposed solution involves equipping all emergency vehicles with GPS devices connected to the traffic management system.

## How is it used?

When an emergency vehicle needs to travel from point A to point B (not necessarily from a designated building such as a hospital or fire station), the destination is input into its GPS. The GPS then communicates this information to the traffic management system.
The AI-based traffic management system (AI-TMS) responds with a calculated route for the vehicle. Notably, this route may not always appear to be the shortest in terms of distance or estimated time. Instead, the AI leverages real-time data on traffic conditions, including congestion, accidents, or other disruptions, to determine the fastest and safest path.
Once the vehicle begins its journey, the AI-TMS tracks its movement and adjusts the traffic lights along the route in advance to minimize delays. By preemptively clearing intersections, the system ensures that the emergency vehicle can pass without unnecessary interruptions.

## Data sources and AI methods

This approach avoids overfitting, as it eliminates the need for the AI to specifically learn to recognize emergency vehicles visually. Instead, data sources such as traffic surveillance cameras provide continuous input for training and testing the system.
For example, historical traffic data from specific intersections can be collected and used to test the AI in real-world scenarios. With this framework, the AI can predict and respond to conditions ahead of time, rather than reacting to emergency vehicles only when they reach an intersection.

## Challenges

Implementing AI-controlled traffic management systems comes with significant challenges:
1.	Real-world Testing: Transitioning from controlled laboratory testing to live traffic conditions is complex and requires careful planning.
2.	GPS Connectivity: Maintaining uninterrupted communication between vehicle GPS devices and the AI system is critical. Redundancy can be introduced by equipping vehicles with backup GPS devices that ensure continuous connectivity and by systems that visually recognize the emergency vehicles. 
3.	Human Factor: The behavior of drivers at intersections may impact the system’s effectiveness. Drivers may perceive the traffic lights as malfunctioning and fail to comply. To address this, flashing lights or other visual indicators at intersections can notify drivers of an approaching emergency vehicle, encouraging cooperation.

## What next?

The potential to save lives by reducing response times and ensuring the safety of emergency vehicles highlights the importance of this project. Initial deployment should begin in smaller municipalities, allowing the system to learn and adapt over time. Once proven effective, it can be scaled up to larger cities with higher traffic density.
Future development could include the capability for the AI-TMS to manage not only routes but also the dispatch of emergency vehicles, prioritizing the most critical situations dynamically.

## Acknowledgments

Inspired by the AI4UTC system, https://www.traffictechnologytoday.com/features/feature-should-ai-control-traffic-lights.html?fbclid=IwY2xjawH42xdleHRuA2FlbQIxMAABHScR_toYluY5bxSUZLoWvGY8xgEDbYDjBJ9ePVlh1KyFQTSIME2OHOFolQ_aem_4vpWTQcJi9is_rjo52-UmQ, and related articles.
The original of the current elaboration is written in Bulgarian language and is translated to English partly with the assistance of ChatGTP.
