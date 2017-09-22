# Interesting book and information
http://gosper.org/Minskys/

# Spirals that I found
circleFactor and rotation typically a positive integer

x -= -rotation * (circleFactor * y + x - rotation * x) / resolution;

y += -rotation * (circleFactor * x - y + rotation * y) / resolution;
