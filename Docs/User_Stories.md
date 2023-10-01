# User Stories - Park It Project

This document outlines user stories for the "Park It" project, a parking management and utilization system.

| User Story | Description | Priority | Linked FR/NFR | Acceptance Criteria |
|------------|-------------|----------|--------------|---------------------|
| US01 | As a user, I want to view a list of nearby parking lots based on my location to quickly find available spaces. | High | FR06 | The system should use my current location to fetch nearby parking lots. The list should display the parking lot name, distance, and availability. I can click on a parking lot to view more details. |
| US02 | As a parking lot owner, I want to register my facility in the "Park It" app to offer parking spaces to users. | High | FR02 | Parking lot owners should provide the facility's name, address, operating hours, the total number of available spaces, and contact details during registration. The registration process should be user-friendly. Parking lot owners should receive a confirmation upon successful registration. |
| US03 | As a user, I want to share my location to automatically find nearby parking lots. | Medium | FR06 | Users should have the option to share their location within the app. Upon sharing location, the system should display nearby parking lots based on the user's current position. |
| US04 | As a user, I want a streamlined process to complete parking space purchases for time efficiency. | High | FR09 | Users should be able to select a parking space and make a purchase with minimal clicks. Payment should be secure and hassle-free. Users should receive a digital parking pass or confirmation. |
| US05 | As a parking lot owner, I want to share real-time parking space availability to attract more customers. | High | FR03 | Parking lot owners should be able to update the availability status of parking spaces in real-time. Users should see real-time availability when searching for parking. |
| US06 | As a user, I expect the "Park It" app to be user-friendly for quick learning and utilization. | High | NFR01 | The app's user interface should be intuitive and easy to navigate. Users should not require extensive training to use the app effectively. |
| US07 | As a user, I want the option to make parking payments directly through the app for convenience. | Medium | FR09 | The app should offer a secure payment gateway for parking fees. Payment options should include popular methods (credit/debit cards, digital wallets, etc.). |
| US08 | As a user, I expect the "Park It" system to process information quickly to minimize wait times. | High | NFR02 | The system should provide fast response times for actions like reservations and payments. Users should not experience significant delays during app usage. |
| US09 | As a parking lot owner, I need the "Park It" system to be reliable and available 100% of the time to ensure uninterrupted business. | High | NFR03 | The system should have robust uptime and reliability measures. Planned maintenance should have minimal impact on availability. |
| US10 | As a user, I want access to online help from any app page for information and support. | Medium | NFR01 | Users should have easy access to an online help center or support resources from any app screen. |

## Requirements Reference

This section references the functional (FR) and non-functional (NFR) requirements associated with the user stories:

| Requirement ID | Requirement Description |
|---------------|-------------------------|
| FR02 | Parking lot owners should be able to register their facilities, providing necessary information including name, address, operating hours, the total number of available spaces, and contact details. |
| FR03 | Parking lot owners should have the capability to manage parking spaces, sharing the availability of parking spaces in their lots, including the number of available spaces at any given moment. |
| FR06 | The platform should integrate maps and navigation functionality, allowing customers to get directions to their reserved parking space. Users of the "Park It" app must be able to share their location, allowing the app to identify nearby registered parking lots. Users of the "Park It" app must be able to view a list of parking lots near their location and check if there are available spaces in each of them, along with the number of available spaces. |
| FR09 | The platform should include a secure payment system for processing parking reservations. |
| NFR01 | The app's user interface should be intuitive and user-friendly, ensuring a short learning curve for users, allowing users to learn it within 30 minutes. - Logged in users should be able to complete the purchase of a parking space with fewer than 5 clicks on the page. The "Park It" application should provide access to online help from any page of the system. The user interface should be intuitive and user-friendly for both parking lot owners and customers. Mobile responsiveness is essential for access from various devices. |
| NFR02 | The "Park It" system should process at least 100 requests per second to ensure responsive performance. The executable size of the "Park It" application should not exceed 200 MB to ensure storage efficiency. The "Park It" system should support the simultaneous use of 1000 users, ensuring high efficiency during peak usage. The platform should handle a high volume of concurrent users and parking lot registrations efficiently. Response times for user actions (e.g., reservations) should be fast. |
| NFR03 | The "Park It" system should be available 100% of the time to ensure availability to users. In case of failure, the "Park It" system should be capable of recovering user data. |