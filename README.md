# Pseudocode for a simple snake hunting game

initialize_game()

while game_is_running:
    handle_player_input()
    move_snake()
    move_target_snake()
    
    if snake_collides_with_target():
        increase_score()
        respawn_target_snake()

    if snake_collides_with_boundary() or time_is_up():
        end_game()

    update_display()

    if player_wants_to_restart():
        reset_game()

