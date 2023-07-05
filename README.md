## ShurjoPay Payment Gateway

ShurjoPay is the first online payment gateway of Bangladesh founded in 2010, when e-commerce was just starting to take off in Bangladesh. An online payment gateway (PG) is a tunnel that connects your bank account to the platform where you need to transfer your money. Not only that, it also connects the MFSs. ShurjoPay acts as an aggregator between their merchants and all the payment services (Banks, MFSs) available in Bangladesh. Using shurjoPay, any e-commerce business, education institute or any other institutes can collect their payments from their users.


### Features
- Support all Bangladeshi Bank
- Support All Bangladeshi Mobile Banking
- Easy Integration
- Personalised payment experience
- Add vat or surcharg

### Configuration

You can install this plugin from Moodle plugins directory or can download from Github.

You can download zip file and install or you can put file under payment/gateway as shurjopay.

### Plugin Global Settings

After installing the plugin you'll automatically redirected to this page.

![shurjopay settings](https://github.com/shadman-ahmed-bs23/laravel-docker-sample/assets/72008371/8c9e3ff5-1464-4ee3-a92d-a44a8a9a3d42)

## Configuring the ShurjoPay Payment Gateway:
### Step: 1
```
Dashboard / Site administration / Plugins / Payment gateways / Manage payment gateways
```
![payment gateway settings](https://github.com/shadman-ahmed-bs23/laravel-docker-sample/assets/72008371/b2e0890d-309b-4a54-b649-b4ed8b2c256d)

Enable Shurjopay plugin 
![enabling shurjopay](https://github.com/shadman-ahmed-bs23/laravel-docker-sample/assets/72008371/8e3ea5d1-ac63-4b76-b5a2-4e5f10a39db4)


### Step: 2
At first create a payment account, from the following path:
```
Dashboard->Site Administration->General->Payment accounts
```
![payment_accounts](https://github.com/shadman-ahmed-bs23/laravel-docker-sample/assets/72008371/e497850b-8465-4b63-a2f2-726a37d6babb)

After creating a payment account, go to the shurjopay settings and fill in the required data: 

```
Dashboard->Site Administration->Plugins->Payment Gateways->shurjopay settings
```
![shurjopay_options](https://github.com/shadman-ahmed-bs23/laravel-docker-sample/assets/72008371/8a80fa20-111d-4201-913b-c7edb1a1d881)

![configuration](https://github.com/shadman-ahmed-bs23/laravel-docker-sample/assets/72008371/3994f7d6-0250-4a0f-8ef7-e2b6711ff212)

- Insert the shurjopay username provided by shurjopay for sandbox
- Insert the shurjopay password provived by shurjopay for sandbox
- Click the "save changes" button to save the information

### Step: 3

Go to the Manage Enrolment Plugins section from the site administration
```
Dashboard->Site Administration->Plugins->Enrolments->Manage Enrol Plugins
```

![image](https://user-images.githubusercontent.com/97436713/153135098-3492f3d1-9dc6-401d-81b1-ad86f6f01494.png)

Enable Enrolment on payment by clicking the eye icon.

## Enrolment Settings for Course:

Now click on the course page and add an enrolment method Enrolment of Payment.

![image](https://user-images.githubusercontent.com/97436713/153138641-93f67f96-9bc1-44bf-afbd-8641b0bd8821.png)

and fill up this form below to set the amount of money and currency for the course payment

![image](https://user-images.githubusercontent.com/40598386/190346195-ca970aa3-4114-4056-9225-7f6e875d0c17.png)

This is how it looks like from a student's perspective:

![image](https://user-images.githubusercontent.com/40598386/190346825-e237a550-b200-4dc2-a46f-e4f1153dd0d6.png)

Select the Payment Type- Shurjopay the surcharge is added with the course payment amount

![payment modal](https://github.com/shadman-ahmed-bs23/laravel-docker-sample/assets/72008371/e5ee26fe-ceb4-4bcd-898b-1b12eff6dfe6)


If your payment is successful then you'll be enrolled in the course.

## Author
- [Brain Station 23 Ltd.](https://brainstation-23.com)

## License
This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see [GNU License](http://www.gnu.org/licenses/).


