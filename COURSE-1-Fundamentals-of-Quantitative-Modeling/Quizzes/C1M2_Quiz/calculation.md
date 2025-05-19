# Question 1
n/a

# Question 2
n/a

# Question 3
n/a

# Question 4
* Cost = 25 + 2.5q
* Let use quantity q = 10
* Cost = 25 + 2.5*10 = 25 + 25 =50

# Question 5
* A website is increasing its user base by 10% each month.  If it has 10,000 users now (t = 0), then how many users does it expect six months from now (t = 6)? Use a discrete model for the growth process.
* P_0 = 10,000
* t = 6
* r = 10% = 0.1
* P_t = P_0 * θ^t = P_0 * (1+r)^t
* P_6 = 10,000 * (1+0.1)^6 = 10,000 * 1.1^6 = 17,715.61 ≈ 17,716

# Question 6
* The number of new domestic wind turbine generators installed each year in a particular country has been forecast to increase at a constant multiplicative rate of 15% per annum for the foreseeable future. This year (t = 0) 100 new generators were installed.  What is the total number of new generators including this year's, that would have been installed within the next ten years (that is up to and including year t = 9)? Use a discrete model for the growth process.
* r=0.15
* P_0=100 at t=0
* t=9
* θ = 1+r = 1+0.15 = 1.15 
* Formula: $ S_t = P_0 * ((1-θ^(t+1)) / (1-θ)) $
* S_9 = 100 * ((1-1.15^(9+1)) / (1-1.15)) = 2030.37 ≈ 2030

# Question 7
n/a

# Question 8
* Using a discount rate of 5%, what is the present value of an investment that provides a lump sum payment of $10,000 in 4 years?
* r=0.05, P_t=10000, t=4
* P_0 = P_t * (1+r)^-t
* P_0 = 10,000 * (1+0.05)^-4 = 8227.02

# Question 9
* The number of users of a cloud based storage service is projected to grow according to the growth model: U_t=1,000,000 e^(0.05 t). What is the best interpretation of the value 1,000,000 in this equation?
* U_t=1,000,000 e^(0.05 t) <=> U_t = U_0*e^rt
* Therefore U_0=1,000,000 = current number of user when t=0

# Question 10
* Consider the demand equation  q=20,000 p^(-1.4). If the cost of production is constant at $0.50 per unit then what is the optimal price to maximize profit?
* We have:
    * Profit = Revenue - Total Cost
    * Revenue = Price * Quantity
    * Total Cost = Cost * Quantity
    * => Profit = (Price * Quantity) - (Cost * Quantity) = Quantity * (Price - Cost)
* Given:
    * Quantity = 20,000 * p^-1.4 = 20,000 * Price^-1.4
    * Cost per unit = $0.50
* Calculation:
    * Profit = Quantity * (Price - Cost)
    * Profit = 20,000 * Price^-1.4 * (Price - Cost)
    * Profit:
        * @ $0.29 = 20,000 * (0.29)^-1.4 * (0.29 - 0.50) = -$23,762.50
        * @ $0.50 = 20,000 * (0.50)^-1.4 * (0.50 - 0.50) = +$0
        * @ $1.40 = 20,000 * (1.40)^-1.4 * (1.40 - 0.50) = +$11,238.11
        * @ $1.75 = 20,000 * (1.75)^-1.4 * (1.75 - 0.50) = +$11,420.54
* Therefore $1.75 is the optimal price to maximize profit.