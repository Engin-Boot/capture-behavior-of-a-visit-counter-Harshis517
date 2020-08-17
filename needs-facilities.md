# Visit-counter for a Facilities Manager

Scenario: Report visitor trends during a week of operation.
Given sensor works perfectly.When the seating capacity is full 
Then there is an alert in the sensor

Scenario: Alert when seating capacity is full
Given the sensor works perfectly. When the seating capacity is full 
Then there is an alert in the sensor.
