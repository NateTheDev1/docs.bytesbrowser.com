---
sidebar_position: 1
---

# Startup

Bytes Browser is a computationally efficient application however it does this through an effective cache policy. Below is a list of things that happen when the application starts up and what you can expect.

```mermaid
flowchart LR
    OnOpen --> Authentication --> Cache --> Index --> Tokenize --> Ready
```

## Authentication

Before Bytes Browser can start it needs to authenticate with the server. This is done to ensure that the application is up to date and that you are using the latest version. This is also done to ensure that you are using a valid subscribed account.

### Offline Usage

Because Bytes Browser is a subscription-based application it requires an internet connection to authenticate. This is done to ensure that you are using a valid subscription. If you are not connected to the internet you will not be able to use the application. However there is a catch, if you have used the application and signed in with an internet connection in the last 20 days you will be able to use the application offline. This is done to ensure that you can use the application when you are not connected to the internet.

## Caching And Indexing

Caching happens on the first run of the application and can take a few minutes to complete. This is because the application is caching every volume on your device. This is done to ensure that the application is as fast as possible when browsing.

## Tokenization

Tokenization runs at first launch after the caching and indexing phase. Tokenization is used to create a searchable index of the files on your device. This is done to ensure that the application is as fast as possible when searching.

## Ready

Once the application has completed the above steps it will be ready to use. You can now search for files and folders on your device.

## Metrics

Currently, the application does not have a metrics page. This is something that will be added in the future however we can use our most recent tests to give you an idea of what to expect.

### Startup Time Metrics (Various Platforms)

| **Type** | **Startup Time**    | **Processor**                |
| -------- | ------------------- | ---------------------------- |
| Windows  | 25-35 seconds       | AMD Ryzen 9                  |
| macOS    | 35-40 seconds       | Apple M1 Chip                |
| Linux    | Not Yet Benchmarked | N/A                          |
| macOS    | Not Yet Benchmarked | AMD Ryzen 2000 & 3000 Series |
| macOS    | Not Yet Benchmarked | AMD Ryzen 5000 Series        |
| macOS    | Not Yet Benchmarked | AMD Ryzen 7000 Series        |
| macOS    | Not Yet Benchmarked | Apple M2 Chip                |
| macOS    | Not Yet Benchmarked | Apple Sillicon Chip          |

:::note

These metrics are not final and are subject to change with performance updates. These metrics are also not complete and will be updated as we test more devices.

:::
