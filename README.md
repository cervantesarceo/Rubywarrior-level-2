Rubywarrior-level-2
===================

Level 2

class Player
  def play_turn(warrior)
    if warrior.feel.empty? 
      warrior.walk!
    else
      warrior.attack!
    end
 
  end
end
