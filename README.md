This is a competition project from de DataCamp competitions

You work for an energy company in Australia. Your company builds solar panel arrays and then sells the energy they produce to industrial customers. The company wants to expand to the city of Melbourne in the state of Victoria. 

Prices and demand for electricity change every day. Customers pay for the energy received using a formula based on the local energy market's daily price.

Your company's pricing committee wants your team to estimate energy prices for the next 12-18 months to use those prices as the basis for contract negotiations.

In addition, the VP of strategy is researching investing in storage capacity (i.e., batteries) as a new source of revenue. The plan is to store some of the energy produced by the solar panels when pricing conditions are unfavorable and sell it by the next day on the open market if the prices are higher.

You have access to over five years of energy price and demand data (source):

"date" - from January 1, 2015, to October 6, 2020.
"demand" - daily electricity demand in MWh.
"price" - recommended retail price in AUD/MWh.
"demand_pos_price" - total daily demand at a positive price in MWh.
"price_positive" - average positive price, weighted by the corresponding intraday demand in AUD/MWh.
"demand_neg_price" - total daily demand at a negative price in MWh.
"price_negative" - average negative price, weighted by the corresponding intraday demand in AUD/MWh.
"frac_neg_price" - the fraction of the day when the demand traded at a negative price.
"min_temperature" - minimum temperature during the day in Celsius.
"max_temperature" - maximum temperature during the day in Celsius.
"solar_exposure" - total daily sunlight energy in MJ/m^2.
"rainfall" - daily rainfall in mm.
"school_day" - "Y" if that day was a school day, "N" otherwise.
"holiday" - "Y" if the day was a state or national holiday, "N" otherwise.
Note: The price was negative during some intraday intervals, so energy producers were paying buyers rather than vice-versa.