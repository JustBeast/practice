practice
========
def reverse(word):
	return word[::-1]
reverse('ball')

def pal(x):
	return x==(x)
pal("toot")

def totpaid(principle, interest, time, ):
		pay = principle * (1+ interest)**time
		return pay
		
	
totpaid(5000, .09, 5,)

def expense(principle, interest, payment):
	total= 0 
	while principle > 0:
		if principle < payment:
			payment= principle
		principle = principle-payment
		total = total + payment 
		principle= principle + interest * principle
	print "Total is $" + str(total)

expense(456, .4, 234)
