---
hidden: true
---

# Setting up correct Time Rate and Mileage Rates (for Business Users)

MyWay Route Planner has outstanding analytics that can provide you with valuable insights, but it's essential to set it up with correct data. For example, it can show you how much money you saved by using an app and can be used to calculate the cost for claiming expenses, for analytics purposes, as a performance report, or for any other purposes.&#x20;

MyWay has two critical parameters we use to calculate the money that the app saved you:&#x20;

1. Time Rate (salary cost, etc.)&#x20;
2. Mileage Rates (petrol cost, remuneration cost, amortization, insurance, etc.)&#x20;

We use Standard Mileage Rates recommended by the government when we provide default Mileage Rates and Salary Average when we provide default cost on Time Rate. You can set up your own salary and mileage rates for better estimation and more accurate cost prediction.&#x20;

### How do we calculate saved costs?&#x20;

It's important to understand how the app calculates Money Saved. Please see the formula we use below:

TimeBO - Time Before Optimization

TimeAO - Time After Optimization

DisBO - Distance Before Optimization

DisAO - Distance After Optimization

$$
Saved Money = (TimeBO - TimeAO) * Time Rate + (DisBO - DisAO) * Mileage Rates
$$

### Useful resources&#x20;

Please find below links to resources that will help you to figure out the Mileage Rates:

{% embed url="https://www.irs.gov/newsroom/irs-issues-standard-mileage-rates-for-2022" %}
IRS Mileage Rates for USA, 2022
{% endembed %}

{% embed url="https://www.canada.ca/en/revenue-agency/services/tax/businesses/topics/payroll/benefits-allowances/automobile/automobile-motor-vehicle-allowances/reasonable-kilometre-allowance.html" %}
Mileage Allowance Rates for Canada, 2022
{% endembed %}

{% embed url="https://www.njc-cnm.gc.ca/s3/d804/en" %}
Mileage Rates for all others countries, 2021-2022
{% endembed %}

Feel free to use your actual salary or any other number as a Time Rate, which can provide you with a better way to track your Time Cost. There are many websites that can provide you with an average pay rate per hour for any sort of jobs out there. You can find it by searching in Google by sentence "courier driver pay rate per hour" and then pick any you trust.
