# Streaming Analytics Pipeline
Many Amazon Web Services (AWS) customers use streaming data to gain real-time insight into customer activity and business trends. Streaming data is generated continuously from thousands of data sources, and this information can help companies make well-informed decisions and proactively respond to changing conditions. Amazon Kinesis is a platform for streaming data on AWS, offering powerful services that make it easy to build data processing applications, load massive volumes of data from hundreds of thousands of sources, and analyze streaming data in real time.

To help customers easily configure a streaming data architecture, AWS offers the Streaming Analytics Pipeline. This solution automatically provisions and configures the AWS services necessary to start consuming and analyzing streaming data in minutes. This solution uses Amazon Kinesis Streams to load streaming data, Amazon Kinesis Analytics to filter and process that data, and Amazon Kinesis Firehose to deliver analyzed data to various data stores for search, storage, or further analytics.

For the full solution overview visit [Streaming Analytics Pipeline](https://aws.amazon.com/answers/big-data/streaming-analytics-pipeline).

## Cloudformation templates
 - cform/streaming-analytics-pipeline.template
 - cform/add-output.template
 - cform/streaming-analytics-pipeline-config.yaml

## Solution code
 - code/streaming-analytics-code.zip
 - code/add-output-code.zip

***

Copyright 2016 Amazon.com, Inc. or its affiliates. All Rights Reserved.

Licensed under the Amazon Software License (the "License"). You may not use this file except in compliance with the License. A copy of the License is located at

    http://aws.amazon.com/asl/

or in the "license" file accompanying this file. This file is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, express or implied. See the License for the specific language governing permissions and limitations under the License.