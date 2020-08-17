# Visit-counter technical needs

Scenario: Recover across restarts of the server
that runs the visit-counter
 Given I have the sensor working
 When I see a serever failure 
 Then I have my server restart.

Scenario: Reconcile counts if the sensor is offline for a while

  Given I have the sensor working
  When I see my sensor is offline
  Then I see the count on my sensor paused
