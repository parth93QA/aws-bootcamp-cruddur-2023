# Week 0 — Billing and Architecture

## Installing AWS CLI/Tasks

I have aws cli installed on my mac machine as I had used some s3 commands previously. I am putting down the steps on how I had installed the same.

![Installing AWS CLI On MACOS](assets/aws-cli.png)

Following instructions were used:

```
curl "https://awscli.amazonaws.com/AWSCLIV2.pkg" -o "AWSCLIV2.pkg"
sudo installer -pkg AWSCLIV2.pkg -target / **in my terminal**

which aws
aws --version
```

![Proof AWS CLI Is Working](assets/aws-cli-proof.png)


### Create a Budget

![Proof Budget Created)(assets/aws-budget.png)

### Create a Billing Alarm

![Proof Billung Alarm Created)(assets/aws-billing-alarm.png)

### Recreate Logical Architecture

![Cruddur Logical Design](assets/Logical-architecture-diagram.png)

.[Lucid Charts share link](https://lucid.app/lucidchart/a2fa5a9f-39a5-4c47-9bdc-524975e14550/edit?viewport_loc=-1311%2C-1287%2C3891%2C2018%2C0_0&invitationId=inv_21a5a132-2167-4dc3-9e70-e05edf1eeb87)


### Alarm Config JSON

```json
![Alarm Config Json](assets/config-billing.json)
```


