# Hot and Cold Data

## 1. Hot and Cold Data

In storage, there are two ways to describe data and its availability: hot or cold.

- Hot data – Data that users access frequently. For example, the data used in mobile apps is hot because users have instant access to their data.
- Cold data – Infrequently or rarely accessed data. An example of cold data is data used for record keeping. You might need to keep this kind of data available, but it doesn’t need to be updated or accessed often.

## 2. Cloud Storage

Cloud Storage is Google’s storage product for unstructured data or objects, including email, web content, images, videos, and audio files.

- Once stored, objects are saved in buckets.
- A bucket is a virtual container that holds objects.
- CSPs categorize storage options into different classes ranging in availability and cost.
- The more available your data needs to be, the more it’ll cost to store.

Cloud Storage offers four different classes for data storage:

1. Standard
2. Nearline
3. Coldline
4. Archival

## 3. Cloud Storage Classes

### 3.1 Standard

- Best for hot data, or data that you need to access frequently, and for short periods of time.
- Data stored in this class is highly available and retrievable in milliseconds.
- Examples:
  - Content used for websites.
  - Gaming platforms.
  - Streaming videos.

Medical Data Example:

If someone is rushed to the hospital for a broken leg, a doctor will collect data for their medical records, like a description of the injury and X-rays.

If the patient needs surgery and physical therapy, it would be best to store their medical data in the standard class, so that it can be accessed quickly.

### 3.2 Nearline

- Best for data that you only need to access up to once a month.
- Nearline is more cost-effective than standard storage.
- A good option for backing up your data.

Medical Data Example:

Once the patient's injuries start to heal, they may move to monthly check-ups. With fewer hospital visits, their records will only need to be accessed once a month. So, their data can be moved into nearline storage.

### 3.3 Coldline

- For people who only need to access their data once every 90 days, or once a quarter.
- Coldline storage is very cost-effective because the data being stored is at rest for long periods of time.

Medical Data Example:

When the patient's leg is almost healed, they'll likely only need to see a doctor once every few months. So, their data can be transferred to coldline storage because doctors no longer need frequent access to their records.

### 3.4 Archival

- Best for archiving or backing up data for disaster recovery purposes.
- Includes data that is accessed very infrequently, or once a year.
- Since there's not as high of a demand for availability, archival storage is also very cost-effective.

Medical Data Example:

When the patient's leg is completely healed, and they no longer need check-ups, their data can be moved to archival storage.

This means the patient's data is still available for retrieval, but will cost the hospital less money to store.

## 4. Key Takeaways

- Storage classes enable you to categorize data to maximize cost savings.
- Many CSPs offer storage services, like Cloud Storage, to accommodate organizations' varying storage needs.
- Cloud Storage's range of classes enable users to choose the best fit for their hot or cold data.
- As a cloud security professional, it'll be important to understand how data is classified in these different storage classes.

## 5. Quick Reference

| Storage Class | Access Frequency    | Primary Use                            |
| ------------- | ------------------- | -------------------------------------- |
| Standard      | Frequently          | Hot data                               |
| Nearline      | Up to once a month  | Backups and infrequently accessed data |
| Coldline      | Once every 90 days  | Long-term storage                      |
| Archival      | Once a year or less | Archiving and disaster recovery        |

