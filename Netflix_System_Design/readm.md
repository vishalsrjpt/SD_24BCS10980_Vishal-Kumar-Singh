NETFLIX SYSTEM DESIGN (24BCS10980_VISHAL KUMAR SINGH)


Functional Requirment:
1. User should able to login / logout and create an account.
2. User should able to purchase subscription securely.
3. User should able to browse any movies or series using keywords.
4. User should able to download the content offline.
5. User should be able to change the resolution of the content they're watching or should able to control the speed.



Non-Functional Requirment:
1. only authinticated user should be able to access the content.
2. there should be very low latency while acessing the content.
3. according to the history of user they should get correct recommendation.
4. payment should be very efficient.
5. Content should be availbale across the globe.



Load Estimation
Daily Active Users = 1,000,000
Peak Concurrent Users: 20% of DAU = 200,000
Average Session Time:2 Hours/User
Peak request = 50,000 requests/sec
Storage: 300 TB
