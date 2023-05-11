# Component Package Three - Companion Controller

## Behaviours
AIStateController

AIState

AIEnemyState

AICompanionState

PickupState

AIEnemyMove

CompanionCount

## AIStateController
This script is the main controller for the companions/enemies. 
It controls which state the companions should be in dependant on the values/inputs it receives.

The variables that can be edited for desired outcome are "Points" (The patrol points that the AI follows when in the enemy state) and "ThrowScript" (The desired throwing script can be used here).

## AIState
This script is the State Machine brain. it is an abstract class and contains the functions "EnterState()", "UpdateState()", "OnTriggerState()" and "OnCollisionState()".

## AIEnemyState
This script is for when the AI is in the enemy state.

## AICompanionState
This script is for when the AI is in the companion state.

## PickupState
This script is for when the AI is ready to be picked up by the player.

## AIEnemyMove
This script moves the AI when it is in the enemy state to the next patrol point position.

## CompanionCount
The variable that can be edited for desired outcome is "CompanionCountText" (the desired TMPro UI object in the scene).
