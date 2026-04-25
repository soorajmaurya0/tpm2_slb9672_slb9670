TPM SLB9672 Firmware Update Tool (Raspberry Pi 5 – Linux)
====================================================

This project documents the usage of Infineon TPM SLB9672 firmware update tools on a Raspberry Pi running Linux.

The tool provided by Infineon Technologies enables users to update the firmware of the TPM 2.0 device on a Linux platform.

📌 Overview

TPM Vendor: Infineon (IFX)

TPM Model: SLB9672

TPM Specification: 2.0

Platform Used: Raspberry Pi (Linux OS)

Purpose: TPM firmware update and capability verification

🖥 System Information

TPM Capability Information (Fixed Properties)

Date : Saturday 29 November 2025 11:27:22 PM IST

TPM_PT_FAMILY_INDICATOR : 2.0
TPM_PT_LEVEL            : 0
TPM_PT_REVISION         : 159
TPM_PT_DAY_OF_YEAR      : 170
TPM_PT_YEAR             : 2020
TPM_PT_MANUFACTURER     : IFX
TPM_PT_VENDOR_STRING    : SLB9672
TPM_PT_VENDOR_TPM_TYPE  : 0
TPM_PT_FIRMWARE_VERSION : 15.23.17664.0

TPM_PT_MEMORY:
    Shared RAM                 : 0 (CLEAR)
    Shared NV                  : 0 (CLEAR)
    Object Copied To RAM       : 1 (SET)

🧰 Requirements

Raspberry Pi (with SPI enabled)

Infineon SLB9672 TPM connected via SPI

Linux OS (Tested on Raspberry Pi OS / Ubuntu)

tpm2-tools

Infineon TPM Firmware Update Tool

Root privileges
