
# Calucating Water Bill

Aim of the code is to calculate the water consumption and bill for
a single apartment at the end of the month.

# Assumptions 

 2 BHK aprtment holds 3 persons \
 3 BHK aprtment holds 5 persons \
 Each person is alloted 10 litres per day  
 Number of days per month is 30 \
 Water Consumption is measured in "Litres" \
 Allotment of Corporation Water and Bore water is based on ratio and
 is done only once at the starting of the month 

 # Costs

   1. Corporation Water - Flat rate of Rs. 1 per litre

   2. Borewell Water - Flat rate of Rs. 1.5 per litre

   3. Tanker Water - Slab rate:

  • 0 to 500L - Rs. 2 per litre \
  • 501L to 1500L - Rs. 3 per litre \
  • 1501 to 3000L - Rs. 5 per litre \
  • 3001L+ - Rs. 8 per litre 

# Sample Test Cases

### INPUT:
ALLOT_WATER 2 3:7 \
ADD_GUESTS 2 \
ADD_GUESTS 3 \
BILL

### OUTPUT:
2400 5215


### INPUT:
ALLOT_WATER 3 2:1 \
ADD_GUESTS 4 \
ADD_GUESTS 1 \
BILL

### OUTPUT:
3000 5750

SAMPLE INPUT-OUTPUT 3

### INPUT:
ALLOT_WATER 2 1:2 \
BILL

### OUTPUT:
900 1200







