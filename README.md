# Analyzing In-Vehicle Coupon Acceptance

This project investigates the factors that influence whether drivers accept coupons for various establishments (such as bars, coffee houses, and restaurants) delivered to their phones while they are driving.

Using data processing and visualization libraries in Python, such as `pandas`, `matplotlib`, `seaborn`, the project aims to identify the demographic and contextual attributes that create the "ideal customer persona" for specific types of coupons.

📓 **[View the Jupyter Notebook](https://github.com/weirui828/coupons4drivers/blob/main/coupon_analysis.ipynb)**

## Key Findings (Bar Coupons)
- **Bar Visit Frequency is Key:** Drivers who already frequent bars (more than 3 times a month) are roughly twice as likely (~76% acceptance) to accept a bar coupon compared to those who go 3 or fewer times a month (~37%).
- **Passenger Demographic:** Drivers traveling with adult passengers (friends or partners) have a significantly higher acceptance rate than drivers who are alone or with children.
- **Ideal Persona:** The ideal target for a Bar coupon is an adult (preferably over 25) who regularly visits bars, is currently driving with adult passengers, and has an income more than $50K per year.

## Key Findings (Coffee House Coupons)
- **Visit Frequency Drives Acceptance:** Frequent coffee house visitors (more than 3 visits/month) have the highest acceptance rate, while non-drinkers still show ~20% acceptance.
- **Expiration Window Matters:** Drivers are more likely to accept coupons that expire in 1 day compared to a 2-hour window, which feels too restrictive.
- **Time of Day:** Acceptance peaks in the late morning and early afternoon, consistent with typical coffee-drinking habits.


## Next Steps
- More comprehensive analysis on all coupon types 
- Systematic analysis using all the factors
- Highlight the discoveries in better ways

## Tools Used
* **Python**
* **Jupyter Notebook** as the primary interactive development environment.
* **Pandas** for data cleaning, filtering, and data manipulation.
* **Seaborn & Matplotlib** for data visualization and statistical analysis.

## Project Structure
* `coupon_analysis.ipynb`: The main Jupyter Notebook containing all data cleaning, visualizations, independent investigations, and final business hypotheses.
* `data/coupons.csv`: The primary dataset containing user attributes, contextual attributes (weather, time, temperature), and coupon attributes.
* `images/`: A folder used to store some of the analysis results (images and plots).

## References
* [Jupyter Notebook](https://jupyter.org/)
* [Pandas Documentation](https://pandas.pydata.org/docs/)
* [NumPy Documentation](https://numpy.org/doc/)
* [Seaborn Documentation](https://seaborn.pydata.org/)
* [Matplotlib Documentation](https://matplotlib.org/stable/)
