all: f
.PHONY: all

# Build
b:
	platformio run

# Regenerate Code
g:
	stm32pio generate

# Flash
f: 
	platformio run --target upload

# clean:
c:
	platformio run --target clean	


