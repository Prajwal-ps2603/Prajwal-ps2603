# RPS.py

def player(prev_play, opponent_history=[]):
    """
    Determines the next move for the player.

    Args:
        prev_play (str): The opponent's last move ("R", "P", or "S").
        opponent_history (list, optional): List of opponent's previous moves. Defaults to [].

    Returns:
        str: The next move ("R", "P", or "S").
    """
    # Your logic here (e.g., random choice, pattern recognition, etc.)
    # For now, let's choose randomly:
    import random
    return random.choice(["R", "P", "S"])
