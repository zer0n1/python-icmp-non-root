I've done very little job to finish it.
changed

	socket.socket(socket.AF_INET, socket.SOCK_RAW, ICMP_CODE)

to

	socket.socket(socket.AF_INET, socket.SOCK_DGRAM, socket.IPPROTO_ICMP)

and We can use non-root user to ping in python.
