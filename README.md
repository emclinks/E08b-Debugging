# E08b-Debugging

This exercise is a game fragment based on the tutorial by GDQuest, and edited for MSCH-G220 Game Technology for the purpose of practicing debugging.

Error 1: In PlayerData.gd under Set_Deaths, New_Score placed where New_Value should've been, preventing game function.
Error 2: 2 indentation errors under Portal.gd preventing game function.
Error 3: Player.gd capitalization error at move_left
Error 4: Enemy sprites were not visible.
Error 5: Capitolization Error on score.text on score_label in UI.gd
Error 6: A row of coins were misplaced on lvl 2, merging into platforms.
Error 7: Capitalization Error on score retrieval on EndScreen.
Error 8: In PlayerData.gd, an unintentional scorecap was placed in set_score, preventing tracking.


# Adjusted another coin position and portal position on level 2 to require all coins to be picked.
# Technical Error: tiles not set high enough, was possible to jump over east side on Level 2 and escape.



The project is associated with a tutorial (both a free and paid version). The free version is in two parts and is available here:
 * [Make Your First 2D Game with Godot: Player and Enemy (beginner tutorial part 1)](https://www.youtube.com/watch?v=Mc13Z2gboEk)
 * [Make Your First 2D Game with Godot: Coins, Portals, and Levels (beginner tutorial part 2)](https://www.youtube.com/watch?v=6ziIyx60N6I)