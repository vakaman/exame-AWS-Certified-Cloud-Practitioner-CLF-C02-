## Cost Alert  

* You can create an alert so that if a resource exceeds a certain amount, AWS notifies you via email, preventing unnecessary expenses, especially due to forgetfulness.  
* CloudWatch can monitor costs through the Billing service.  

---

### Enabling Billing for CloudWatch  

* **Menu**  
    * **Account**  
        * **Billing Preferences**  
        * **Alert Preferences**  
            * **CloudWatch Billing Alerts** → (Must be Enabled)  

* **CloudWatch**  
    * **All Alarms**  
        * **Create Alarm**  
        * Select **Metrics**  
        * In this case, we will use **Total Account Billing**  
        * Set the condition of interest, e.g., **>= $10**  
        * Configure the notification service to use **SNS**  
        * Create an **SNS Topic** with your email as the destination  
        * Confirm your **email subscription** to the notification topic  
