## 🎓🔥 STARGATE, a gateway for multi models data API 🔥🎓

[![License Apache2](https://img.shields.io/hexpm/l/plug.svg)](http://www.apache.org/licenses/LICENSE-2.0)
[![Discord](https://img.shields.io/discord/685554030159593522)](https://discord.com/widget?id=685554030159593522&theme=dark)

![image](pics/splash.png?raw=true)

This intructions will lead you to step by step operations for the workshop on ASTRA + STARGATE for ApiDays Helsinki

## 1. Create Astra Instance

**`ASTRA`** is the simplest way to run Cassandra with zero operations at all - just push the button and get your cluster. No credit card required, $25.00 USD credit every month, roughly 5M writes, 30M reads, 40GB storage monthly - sufficient to run small production workloads.  

✅ Register (if needed) and Sign In to Astra [https://astra.datastax.com](https://dtsx.io/workshop): You can use your `Github`, `Google` accounts or register with an `email`.

_Make sure to chose a password with minimum 8 characters, containing upper and lowercase letters, at least one number and special character_

✅ Create a "pay as you go" plan

Follow this [guide](https://docs.datastax.com/en/astra/docs/creating-your-astra-database.html), to set up a pay as you go database with a free $25 monthly credit.

- **Select the pay as you go option**: Includes $25 monthly credit - no credit card needed to set up.

You will find below which values to enter for each field.

- **For the database name** - `free_db.` While Astra allows you to fill in these fields with values of your own choosing, please follow our recommendations to ensure the application runs properly.

- **For the keyspace name** - `free`. It's really important that you use the name "free" for the code to work.

_You can technically use whatever you want and update the code to reflect the keyspace. This is really to get you on a happy path for the first run._

- **For provider and region**: Choose and provider (either GCP or AWS). Region is where your database will reside physically (choose one close to you or your users).

- **Create the database**. Review all the fields to make sure they are as shown, and click the `Create Database` button.

You will see your new database `pending` in the Dashboard.

![my-pic](https://github.com/datastaxdevs/shared-assets/blob/master/astra/dashboard-pending-1000-update.png?raw=true)

The status will change to `Active` when the database is ready, this will only take 2-3 minutes. You will also receive an email when it is ready.

