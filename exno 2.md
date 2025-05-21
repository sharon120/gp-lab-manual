# EXP-02: Create A Player Movement Using Pawn, Collectable, Player Health And Score.
## Date: 12/03/2025
## Aim:
To Create a player movement using pawn, collectible, player health and score.

## Procedure To Create and Destroy the coin:
1. Create a new project in Unreal Engine and choose a template that suits your needs.
2. Add a new actor to the level and call it "Coin".
3. Create a new blueprint based on the Coin actor by selecting it in the Content Browser and choosing "Create Blueprint".
4. Open the Coin blueprint and add a static mesh component to represent the coin.
5. Add a collision component to the Coin blueprint so that the player can interact with it.
6. Create a new blueprint based on the player character.
7. Open the player blueprint and add a collision component to represent interaction with coins.
8. Add an event to the player blueprint for coin collision.
9. Check if the coin is already collected. If not, set `IsCollected = true` and update the score.
10. Destroy the collected coin.
11. Add several instances of the coin in the level, spaced out nicely.

## Procedure To Redirect to levels:
1. Open the Level Blueprint or relevant Blueprint for level transitions.
2. Create triggers (e.g., Box Trigger) in your level to detect player overlap.
3. Add logic using "OnComponentBeginOverlap" to trigger level change.
4. Use the "Open Level" node in Blueprint and specify the target level name.
5. Create multiple levels under your project directory.
6. Ensure all levels are added to the project’s Level list in World Settings.
7. Connect different triggers to different level names to allow branching.
8. Test transitions between levels using Play In Editor (PIE).
9. Add UMG widgets for feedback (like “Level Complete!”).
10. Use delay nodes or animations if needed before level redirection.

## Output:
![image](https://github.com/user-attachments/assets/0d3d80d8-bf5c-45d6-ad66-c46385f32a5a)
![image](https://github.com/user-attachments/assets/505948ce-cbc3-4640-b51e-b3241f7b3ba3)
![image](https://github.com/user-attachments/assets/acc151d9-c416-4935-a9c7-0be216b023e7)


## Result:
Thus, To Create a player movement using pawn, collectible, player health, and score created and developed by unreal Engine.
