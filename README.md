Problem Statement -

Udgir is a small city with a municipal council in the Latur district, which is located in the Indian state of Maharashtra and facing one the most common problem which even most of the big Cities face which is – There is no definitive route which is followed for collection of Waste from respective areas and which often and in turn leads to waste not being collected at proper time and having really no definitive knowledge of exactly which area produce how much of Waste, for trips to be optimally scheduled Not enough Waste being processed out of the total waste collected. According to officials of municipality of Udgir one of the reason that this is causing is the guess work and uncertainty in the amount of waste collected next day.

Proactively, getting an estimate of amount of Wet Waste will help officials to plan and make necessary arrangement for upcoming days. Ie. like making an compost, fertilizer etc

Data Collection – Permission and Site Visit

![WhatsApp Image 2021-08-04 at 11 15 38 PM](https://user-images.githubusercontent.com/81433469/128229512-b724a4d1-372e-46e4-b14d-9203e4d4e7b3.jpeg)

![WhatsApp Image 2021-08-04 at 11 15 44 PM](https://user-images.githubusercontent.com/81433469/128229531-596665a7-0d89-436f-bd98-a6057a638316.jpeg)

Data – For different Wards

Sample Data in Raw format for Ward A -

![WhatsApp Image 2021-08-04 at 11 15 51 PM](https://user-images.githubusercontent.com/81433469/128229611-9d92f4e5-075a-4435-9764-868b8e726de3.jpeg)

Similarly, there are total 4 Wards and data is present for Ward A, B, C and D

Encoded Data – In Excel.

Making Sense of Data

Date, Day, Ward, Vehicle Number (from where the Waste is collected from every Area)are entered as it is and then for Route we have defined specific labels. That means – Every Route from where the Waste is picked are set of Locations Predefined. Time - Recorded time at which Data is dumbed in the Ground Waste (Kgs ) is the waste the Vehicle brought Animal found in that area for that Location/Route by that Vehicle Number

Final Excel Data -

![WhatsApp Image 2021-08-04 at 11 15 58 PM](https://user-images.githubusercontent.com/81433469/128229645-26b0ccbe-19e5-4ee7-9e59-dee4e186765a.jpeg)

Following is the way we defined our label for each Route -

![WhatsApp Image 2021-08-04 at 11 16 03 PM](https://user-images.githubusercontent.com/81433469/128229715-9f8e5201-105e-49a9-973b-1e71af4f8b30.jpeg)

Data Preprocessing, Data Cleaning and EDA -

Of course, the manually entered Data had many typing errors as well the data in the raw format had null values, zeros and blank spaces which are treated Missing Value Imputation and Data Cleaning is done (Detailed Explanation in the ipynb file) After, the same EDA is done – Univariate and Bivariate Analysis, plots and graphs which focusses and aims at finding the pattern, distribution and type of Data

Making Sense of the Data – Bird’s Eye View

![WhatsApp Image 2021-08-04 at 11 16 11 PM](https://user-images.githubusercontent.com/81433469/128229760-718f181a-0ce6-4f35-b5a7-6240d8dbe78d.jpeg)

Using Regression Model Approach

![WhatsApp Image 2021-08-04 at 11 16 18 PM](https://user-images.githubusercontent.com/81433469/128230067-ab290a9a-4e3a-4990-a88b-8aa8751415fb.jpeg)

Classification model

![WhatsApp Image 2021-08-04 at 11 16 21 PM](https://user-images.githubusercontent.com/81433469/128229868-8341db00-3873-454c-81af-15195d6bcef2.jpeg)

Conclusion

Given, Ward, Vehicle Number, Route, and other details we offer solution which enables any employee of the Municipality to optimize and automate planning of waste collection routes. https://waste-estimation.herokuapp.com Finally, we deployed the same using Flask and Heroku

Input -

![WhatsApp Image 2021-08-04 at 11 16 28 PM](https://user-images.githubusercontent.com/81433469/128229911-bc6e8e50-953a-43ea-a4c4-cd425fc377a4.jpeg)

Output -

![WhatsApp Image 2021-08-04 at 11 16 34 PM](https://user-images.githubusercontent.com/81433469/128229935-207b9f90-c472-40b0-8403-18f7186092bc.jpeg)

Future Scope

1. Optimal Route Planning for waste collection using Operation Research Techniques
2. Asset Management for trash bins for effective management
3. Eventually setting up the system to – Asset Management, Waste Monitoring and Route Planning solution which can then finally be delivered to the Government as a complete end to end solution.



Note - This Project is done with authorization from Udgir Muncipal Corportaion, hence the dataset cannot be shared nor distributed publicly. Above is the methodology and solution we proposed. Strictly no permission for copyright or any infringement.
