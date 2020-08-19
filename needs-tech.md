# Visit-counter technical needs

Scenario: Recover across restarts of the server
that runs the visit-counter
 Given: An active sensor connected to central controller
 When: Server restarts from any state.
 Then: Aggregate the manual log and latest server log and feed to the system.

Scenario: Reconcile counts if the sensor is offline for a while

  Given: An active sensor connected to central controller system.
  When: Server comes back online from offline state.
  Then: Aggregate the manual log count and latest server log and feed to controller.
