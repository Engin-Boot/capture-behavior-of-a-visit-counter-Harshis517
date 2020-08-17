# Visit-counter for a Director

Scenario: Show patient visits during working days and holidays

  Given I have the sensor working
  When I see patients entering on a particular day
  Then I see a recording in my sensor

Scenario: Compute parking slots to reserve for visiting specialists

  Given I have the sensor working
  When I see specialists entering on a particular day
  Then I see a recording against the parking lot in my sensor
