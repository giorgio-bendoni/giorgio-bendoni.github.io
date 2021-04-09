---
layout: page
---

<h3>Growth Rates</h3>

If some variable x (for example, the number of gallons of gasoline sold in a week) changes from x1 to x2, then we can define the change in that variable as Δx = x2 − x1. But there are difficulties with this simple definition. The number that we calculate will change, depending on the units in which we measure x. If we measure in millions of gallons, x will be a much smaller number than if we measure in gallons. If we measured x in liters rather than gallons (as it is measured in most countries), it would be a bigger number. So the number we calculate depends on the units we choose. To avoid these problems, we look at percentage changes and express the change as a fraction of the individual value. In what follows, we use the notation %Δx to mean the percentage change in x and define it as follows: %Δx = (x2 − x1)/x1. A percentage change equal to 0.1 means that gasoline consumption increased by 10 percent. Why? Because 10 percent means 10 “per hundred,” so 10 percent = 10/100 = 0.1.

Very often in economics, we are interested in changes that take place over time. Thus we might want to compare gross domestic product (GDP) between 2012 and 2013. Suppose we know that GDP in the United States in 2012 was $14 trillion and that GDP in 2013 was $14.7 trillion. Using the letter Y to denote GDP measured in trillions, we write Y2012 = 14.0 and Y2013 = 14.7. If we want to talk about GDP at different points in time without specifying a particular year, we use the notation Yt. We express the change in a variable over time in the form of a growth rate, which is just an example of a percentage change. Thus the growth rate of GDP in 2013 is calculated as follows:

$$\%\Delta Y = \frac{Y_{2013} - Y_{2012}}{Y_{2012}} = \frac{14.7 - 10}{14} = 0.05$$


The growth rate equals 5 percent. In general, we write %ΔYt+1 = (Yt+1 − Yt)/Yt. Occasionally, we use the gross growth rate, which simply equals 1 + the growth rate. So, for example, the gross growth rate of GDP equals Y2013/Y2012, or 1.05.

There are some useful rules that describe the behavior of percentage changes and growth rates.

The Product Rule. Suppose we have three variables, x, y, and z, and suppose

x = yz.
Then

%Δx = %Δy + %Δz.
In other words, the growth rate of a product of two variables equals the sum of the growth rates of the individual variables.

The Quotient Rule. Now suppose we rearrange our original equation by dividing both sides by z to obtain

If we take the product rule and subtract %Δz from both sides, we get the following:

%Δy = %Δx − %Δz.
The Power Rule. There is one more rule of growth rates that we make use of in some advanced topics, such as growth accounting. Suppose that

y = xa.
Then

%Δy = a(%Δx).
For example, if y = x2, then the growth rate of y is twice the growth rate of x. If then the growth rate of y is half the growth rate of x (remembering that a square root is the same as a power of ½).

### More Formally

Growth rates compound over time: if the growth rate of a variable is constant, then the change in the variable increases over time. For example, suppose GDP in 2020 is 20.0, and it grows at 10 percent per year. Then in 2021, GDP is 22.0 (an increase of 2.0), but in 2022, GDP is 24.2 (an increase of 2.2). If this compounding takes place every instant, then we say that we have exponential growth. Formally, we write exponential growth using the number e = 2.71828.… If the value of Y at time 0 equals Y0 and if Y grows at the constant rate g (where g is an “annualized” or per year growth rate), then at time t (measured in years),

$$ Y_t = e^{gt}Y_0 $$

A version of this formula can also be used to calculate the average growth rate of a variable if we know its value at two different times. We can write the formula as

$$ e^{gt} = \frac{Y_t}{Y_0} $$

which also means

$$ gt = \ln{\frac{Y_t}{Y_0}} $$

where \ln is the natural logarithm. Dividing by t we get the average growth rate

$$ g = \frac{\ln{\frac{Y_t}{Y_0}}}{t} $$

For example, suppose GDP in 2020 is 20.0 and GDP in 2030 is 28.0. Then Y2030/Y2020 = 28/20 = 1.4. Using a calculator, we can find ln(1.4) = 0.3364. Dividing by 10 (since the two dates are 10 years apart), we get an average growth rate of 0.034, or 3.4 percent per year.

### Mathematical appendix
***

If a variable \[ x \] has a value of $x_0$ today and grows at a rate \(r\) over a period of time \(t\), the value of \(x\) at the end of the period of time \(t_1\) will be

$$ x_1 = x_0 + r \times x_0 = x_0 \times (1+r)$$

After compounding over \[ n \] periods, the value of $x$ will be

$$x_n = x_0 \times (1+r)^n$$

The above formula can be written 

$$ X_n = X_0 \times (1 + \frac{365}{n})^{nt} $$

where it is assumed that the time period t is of 365 days, and that compounding is calculated n times year. 


