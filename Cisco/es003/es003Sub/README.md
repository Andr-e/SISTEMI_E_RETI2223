Compito per il 3 ottobre 2022

Creare 5 sottoreti:

				-Rete: A 14hosts
				-Rete B:  28hosts
				-Rete C:  2hosts
				-Rete D:  7hosts
				-Rete E:  28hosts

Indirizzo iniziale è: 192.168.5.0/24

-Per prima cosa si parte dalle reti più grandi:

Rete B

	La rete B richiede 5 bit, perché 2^5 -2 fa 30, quindi ci stanno
  
	IP Net: 192.168.5.0/27
  
	SubNet: 255.255.255.224
  
	BroadCast: 
  
				11000000.10101000.00000101.00000000
        
				OR
			       00000000.00000000.00000000.00011111
				=
				11000000.10101000.00000101.00011111
        
					192.168.5.31
          
Rete E
	Ha bisogno sempre di 5 bit come la rete B
  
	Net: 192.168.5.32
  
	SubNet: 255.255.255.224
  
	BrodCast:  
  
				11000000.10101000.00000101.00100000
        
				OR
        
			     00000000.00000000.00000000.00011111
				= 
					192.168.5.63
					
Rete A

	Ha bisogno di 4 bit, perché 2^4 fa 16 -2 = 14 
  
	IP Net:192.168.5.64 / 28
  
	Sub Net: 255.255.255.240
  
	BroadCast: 
  
				11000000.10101000.00000101.01000000
        
				OR
			        00000000.00000000.00000000.00001111
				=
				11000000.10101000.00000101.01001111
        
					192.168.5.79
          
Rete D

	Ha bisogno di 4 bit
  
	IP Net:192.168.5.80 / 28
  
	Sub Net: 255.255.255.240
  
	BroadCast: 
  
				11000000.10101000.00000101.01010000
        
				OR
			        00000000.00000000.00000000.00001111
				=
        
				11000000.10101000.00000101.01011111
        
					192.168.5.95
          
 Rete C
 
	Ha bisogno di 2 bit
  
	IP Net:192.168.5.96 / 30
  
	Sub Net: 255.255.255.252
  
	BroadCast: 
  
				11000000.10101000.00000101.01100000
        
				OR
			        00000000.00000000.00000000.00000011
				=
        
				11000000.10101000.00000101.01100011
        
					192.168.5.99

				
