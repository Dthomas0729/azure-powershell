## 16.0.0 - June 2026
#### Az.Compute 11.6.0 
* Modified cmdlet `New-AzRestorePoint`
   - Added parameter `-InstantAccessDurationInMinutes`
* Modified cmdlet `New-AzRestorePointCollection`
   - Added parameter `-InstantAccess`
* Modified cmdlet `Update-AzRestorePointCollection`
   - Added parameter `-InstantAccess`
#### Az.Monitor 8.0.0 
* Modified cmdlet `New-AzPipelineGroup`
   - Removed parameter `-NetworkingConfiguration`
   - Added parameters `-DistributionMaxInstancesPerHost`, `-ExecutionPlacementConstraint`, `-TlsConfiguration`
* Modified cmdlet `Update-AzPipelineGroup`
   - Removed parameter `-NetworkingConfiguration`
   - Added parameters `-DistributionMaxInstancesPerHost`, `-ExecutionPlacementConstraint`, `-TlsConfiguration`
#### Az.Network 8.0.0 
* Modified cmdlet `New-AzFirewallPolicy`
   - Changed the type of parameter `-UserAssignedIdentityId` from `String` to `String[]`
* Modified cmdlet `Set-AzFirewallPolicy`
   - Changed the type of parameter `-UserAssignedIdentityId` from `String` to `String[]`


