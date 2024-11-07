## Response Block Completed
Yes
## Domain
TriCore Debugging
## Response
To ensure that all System Timer Modules (STMs) are suspended immediately when program execution halts, two conditions must be met:

1. Global Peripheral Suspend must be enabled. You can use the command SYStem.Option.PERSTOP ON to activate this feature.

2. Each System Timer Module must be configured to allow suspension. For STM0, you can use the command PER.Set.ByName .STM0_OCS.SUS “Set Suspended”. Similar commands are available for the other STMs.

## Links 
debugger_tricore.fm, (T32Heading1) Debugging, (T32Heading2) Suspending Peripherals
## Downgrading
No 
## Test Configuration
general_set, tricore_set
## Disabled Manuals
none
## Tasks for the Manual Team
Yes
## Task Description
**app_tricore_flash.pdf:**
(T32Heading1) Organization of TriCore FLASH Scripts, (T32Heading2) FLASH Demo Scripts
This link is not needed.