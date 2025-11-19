📊 Bank Advertising Campaign – Coupon Usage Analysis

This project analyzes a bank’s marketing campaign to understand which factors influence whether a customer uses a promotional coupon. The analysis is based on a logistic regression model using three key variables: Channel, Bundle Offer, and their interaction.

📁 Dataset Description

The dataset contains the following variables:

IFUseCoupon
Binary target variable indicating whether the customer used the coupon (Yes/No).

IFBundle
Indicates whether the customer received a bundle offer (Bundle / NoBundle).

Channel
The communication channel used in the campaign:

Online

Mail

InPerson

🧠 Objective

To model and predict the probability that a customer uses the coupon based on:

Whether they received a bundle offer

The channel through which the offer was delivered

The interaction between bundle and channel

📈 Key Findings

Bundle offers increase the likelihood of using a coupon overall.

InPerson and Mail channels show significantly higher coupon usage compared to Online.

The interaction effects are negative, meaning the impact of bundle offers is weaker when combined with Mail or InPerson channels.

The deviance test indicates that the model fits significantly better than a null model.

📂 Project Structure
project/
│── data/
│── scripts/
│── results/
│── README.md

✔️ Notes

This project demonstrates statistical modeling for marketing decision-making, including interpretation of coefficients and evaluation of model fit.


📬 Contact

For questions, feel free to open an issue or reach out.
