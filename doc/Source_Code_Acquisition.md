# Source Code Acquisition

-   [About SDV](#about-sdv)
-   [When to Use](#when-to-use)
-   [Preparations](#preparations)
-   [Operations](#operations)
-   [Source Code Directories](#source-code-directories)

## About SDV
For SDV overview , please refer to [Overview](../README.md#overview)

## When to Use

-   You want to establish a baseline based on SDV releases and distribute the baseline to your customers.

-   You have interconnected your software with SDV platform.

-   You want to contribute code to SDV platform.

-   You need to address SDV platform issues.

-   You want to learn SDV platform source code.


## Preparations

1.  Register your account with github.
2.  Register an SSH public key.
3.  Install the git client and configure basic information.

    ```
    git config --global user.name "yourname"
    git config --global user.email "your-email-address"
    ```

## Operations 

Run the  **git clone**  command to clone single code repository.

SDV baseline:

```
git clone https://github.com/autocore-ai/sdv
```

PCU2.0 mcu baseline, including zenoh:

```
git clone https://github.com/autocore-ai/pcu_mcu_hal -b HAL_dev_2.0
```
AutoCore Simulator:

```
git clone https://github.com/autowarefoundation/autocore_sim
```

Automation Test:

```
git clone https://github.com/autocore-ai/ats-script
```

## Source Code Directories 

The following table describes the SDV platform source code directories.

**Table  **  Directory description
