---
auto_validation: true
title: Create an SAP Cloud Platform ABAP Environment Trial User
description: Create an trial user and ABAP cloud project with SAP Cloud Platform ABAP environment.
primary_tag: products>sap-cloud-platform--abap-environment
tags: [  tutorial>beginner, topic>abap-development, products>sap-cloud-platform ]
time: 5
author_name: Merve Temel
author_profile: https://github.com/mervey45
---

## Prerequisites  
 - You have created a **trial account on SAP Cloud Platform**:  [Get a Free Trial Account on SAP Cloud Platform](hcp-create-trial-account).

## Details
### You will learn  
  - How to create an trial user
  - How to create an ABAP Cloud project

**Currently, only Europe (Frankfurt) is available as a region in the Cloud Foundry Trial.**

---
[ACCORDION-BEGIN [Step 1: ](Select ABAP Trial)]
  1. Logon to your SAP Cloud Platform Trial Cockpit <https://cockpit.hanatrial.ondemand.com/> and select **Enter Your Trial Account**.

      ![Select ABAP Trial](welcome.png)

  2. **You can see your trial subaccount with Europe (Rot) as region**.

      Click **trial**.

      ![Select ABAP Trial](welcometrial.png)

  3. Select **Spaces**.

      ![Select ABAP Trial](space.png)

  4. Click **dev** to navigate to your dev space.

      ![Select ABAP Trial](dev.png)

  5. Click **Services**.

      ![Select ABAP Trial](account3.png)

  6. Click **Service Marketplace**.

      ![Select ABAP Trial](account4.png)

  7. **If you see the ABAP Trial tile, then select it move on with step 3.1 to create your instance**.

     **If you don't see the ABAP Trial tile, then move on with step 2.1 to configure your SAP Cloud Platform Entitlements.**.

      ![Select ABAP Trial](trial.png)

[DONE]
[ACCORDION-END]

[ACCORDION-BEGIN [Step 2: ](Configure SAP Cloud Platform Entitlements)]

  1. **Skip step 2**, if you could enter **ABAP Trial**.

     Otherwise configure your entitlements to make your ABAP Trial tile visible. Switch to your global account and select **Entitlements**.

      ![Select ABAP Trial](entitlement5.png)

  2. Select **Subaccount Assignments**.

      ![Select ABAP Trial](entitlement6.png)

  3. Select **trial** as subaccounts and click **Go**.

      ![Select ABAP Trial](entitlement7.png)

  4. Click **Configure Entitlements**.

      ![Select ABAP Trial](entitlement9.png)

  5.  Click **Add Service Plans**.

      ![Select ABAP Trial](entitlement10.png)

  6.  Select **ABAP Trial**, check **shared** and click **Add 1 Service Plan**.

      ![Select ABAP Trial](entitlement11.png)

  7.  Click **Save**.

      ![Select ABAP Trial](entitlement13.png)

  8.  Check your result

      ![Select ABAP Trial](entitlement14.png)

  9.  Go back to your space dev, select **Service Marketplace** and **ABAP Trial**.

      ![Select ABAP Trial](abaptrial.png)

[DONE]
[ACCORDION-END]

[ACCORDION-BEGIN [Step 3: ](Create instance)]
  1. You can create a new instance on the SAP Cloud Platform ABAP Environment Trial. Therefore select **Instances**.

      ![Create instance](instance.png)

  2. Click **New Instance**.

      ![Create instance](instance2.png)

  3. Click **Next**.

      ![Create instance](instance3.png)

  4. Add your e-mail address. Your e-mail address must be your Cloud Foundry Trial e-mail address.

      - "email": "example@email.com"

     Click **Next**.

      ![Create instance](instance4.png)

  5. Click **Next**.

      ![Create instance](instance5.png)

  6. Create an instance:

     - Instance Name: `<your_name>`

     Click **Finish**.

      ![Create instance](instance6.png)

  7. Now your instance appears on the instance overview.

      ![Create instance](instance7.png)

[DONE]
[ACCORDION-END]

[ACCORDION-BEGIN [Step 4: ](Create service key)]
  1. Click on your instance.

      ![Create service key](key.png)

  2. Select **Service Keys**.

      ![Create service key](key0.png)

  3. Click **Create Service Key**.

      ![Create service key](key2.png)

  3. Create a service key:

     - Name: ADT

     Click **Save**.

      ![Create service key](key3.png)

  4. Now your service key appears. Copy your service key for later use.
     The service key enables the connection to the SAP Cloud Platform ABAP environment system in ADT.

     ![Create service key](key4.png)

[DONE]
[ACCORDION-END]

[ACCORDION-BEGIN [Step 5: ](Open ABAP Development Tools )]
For TechEd users:

Click **>>** on your windows taskbar and select **SAP Development Tools** > **ABAP in Eclipse - `CAA361`**.  

![Create service definition](adt.png)

For other users:

Open your local ABAP Development Tools (ADT). You can download the latest version from <https://tools.hana.ondemand.com/#abap>.

[DONE]
[ACCORDION-END]


[ACCORDION-BEGIN [Step 6: ](Create ABAP cloud project)]
  1. Select **File** > **New** > **ABAP Cloud Project**.

      ![Create ABAP cloud project](project.png)

  2. Select **Service Key** and click **Next >**.

      ![Create ABAP cloud project](project2.png)

  3. Paste your service key and click **Next >**.

      ![Create ABAP cloud project](project3.png)

  4. Logon to your ABAP trial account with your e-mail address and password.

      ![Create ABAP cloud project](project4.png)

  5. Click Finish.

      ![Create ABAP cloud project](project5.png)

  6. Your trial system appears on the project explorer.

      ![Create ABAP cloud project](project6.png)

[DONE]
[ACCORDION-END]


[ACCORDION-BEGIN [Step 7: ](Test yourself)]

[VALIDATE_1]
[ACCORDION-END]
---
