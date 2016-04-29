# payline-java

[![Circle CI](https://circleci.com/gh/finix-payments/payline-java.svg?style=svg&circle-token=bd006401ffc2907c157e112576504319f0d83523)](https://circleci.com/gh/finix-payments/payline-java)

## Usage
See test class [ProcessingClientScenarioTest](https://github.com/finix-payments/payline-java/blob/master/src/test/java/io/payline/payments/processing/client/ProcessingClientScenarioTest.java) for more details.

## Version history
- 1.0.0-SNAPSHOT

## Requirements
Java 8 or later

## Maven
```xml
<dependency>
  <groupId>io.payline.payments.processing.client</groupId>
  <artifactId>payline</artifactId>
  <version>${version}</version>
</dependency>
```
Config repository url for snapshot
```xml
<repositories>
  <repository>
    <id>oss-snapshots</id>
    <url>https://oss.sonatype.org/content/repositories/snapshots</url>
    <snapshots>
      <enabled>true</enabled>
    </snapshots>
  </repository>
</repositories>
```
