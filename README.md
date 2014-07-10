SonicPi
=======

Sonic Pi code for various songs - not necessarily correct!

#Electro House 1



with_tempo 350



in_thread do
  
  with_synth "saw_beep"
  
  16.times do
    
    play 47
    
    sleep 1
  
  end

end


# riff 1 repeats x2


2.times do

play_pattern [59, 64, 59, 64]

play_pattern [59, 62, 59, 62,59, 62]

play_pattern [59, 61, 59, 61,59, 61

play_pattern [59, 62, 59, 62, 59, 61, 59, 62]

end



# riff 2 repeats x2


2.times do

play_pattern [59, 64, 59, 64]

play_pattern [59, 66, 59, 66,59, 66]

play_pattern [59, 61, 59, 61,59, 61]

play_pattern [59, 62, 59, 62, 59, 61, 59, 62]

end

