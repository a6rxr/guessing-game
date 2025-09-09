README.md: guessinggame.sh
	@printf "# Guessing Game Project\n\n" > README.md
	@printf "Generated: " >> README.md
	@date >> README.md
	@printf "\nNumber of lines in guessinggame.sh: " >> README.md
	@wc -l < guessinggame.sh >> README.md
