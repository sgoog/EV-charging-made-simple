# EV-charging-made-simple

I'm still somewhat enthusiastic about EV driving, especially after replacing a diesel car
with an EV and driving the shorter distances with it up to 250 km. My tests revealed that
very short distance drives of 2 km or so often take 13 l/100 km when done with an efficient
1.6 l gasoline engine which means it consumes 11 times the 10 kWh/100 km the EV "burns".
And we achieved consumptions down to 8.5 kWh/100 km in urban area.

Goal is to only charge sunlight although we've been using 100% from renewable energy plants
for past 15 years but still it's possible to avoid network traffic and transformation loss.

This project is about charging an EV without a wall box but depending on sunlight power.
Charging only while PV power exceeds household consumption leads to the question on whether
a wallbox and high charging current are even needed.

Another use case, if no PV generator is available, could be a load control/balancing purpose.
I'm interested in feedback on your own re-implementations, especially further developing it
towards server-side implementation in order to start/stop/monitor it on a NAS with webserver.

My equipment is a regular "Alibaba" charging cable or the one by Volkswagen with only 10 A,
a Shelly 1 PM for switching (it has power and temperature meters and WLAN), a Shelly 3EM for
monitoring the network power in/out (has power meters for 3 phases and WLAN) and just for
information the built-in web interface of the PV generator KACO TL3 10.0. Except the latter
total cost was less than 250 €. 
