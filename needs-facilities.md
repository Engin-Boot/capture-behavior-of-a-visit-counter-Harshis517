# Visit-counter for a Facilities Manager

Scenario: Report visitor trends during a week of operation.
Given I have a counter sensor that's turned on.
When the patients enters the hospital 
Then I see a count in the sensor.

Scenario: Alert when seating capacity is full
Given the sensor works perfectly. When the seating capacity is full 
Then I see an alert in the sensor.
