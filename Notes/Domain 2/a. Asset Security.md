## 2.1 - Identify and classify information and assets

- Data classification
- Asset Classification

## 2.2 - Establish information and asset handling requirements

## 2.3 - Provision information and assets securely

- Information and asset ownership
- Asset inventory (e.g., tangible, intangible)
- Asset management

## 2.4 - Manage data lifecycle

- Data roles (i.e., owners, controllers, custodians, processors, users/subjects)
- Data collection
- Data location
- Data maintenance
- Data retention
- Data remanence
- Data destruction

## 2.5 - Ensure appropriate asset retention (e.g., End of Life (EOL), End of Support)

## 2.6 - Determine data security controls and compliance requirements

- Data states (e.g., in use, in transit, at rest)
- Scoping and tailoring
- Standards selection
- Data protection methods (e.g., Digital Rights Management (DRM), Data Loss Prevention (DLP), Cloud Access Security Broker (CASB))


## Areas for Review
- Data Lifecycle

## Missed Questions
- collection limitation - minimize the amount of data they collect and store
	- This is something that should be considered before more technical data protection controls (anonymization)
- Data Destruction Methods

| Method                 | Thoroughness                                                                                                | Purpose                                              | Methods                                                                    | Recoverability                                       |
| ---------------------- | ----------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- | -------------------------------------------------------------------------- | ---------------------------------------------------- |
| Erasing (deleting?)    | Not thorough - data remains on the drive                                                                    | Not valid for data destruction                       | Delete operation againsta a file                                           | Anyone can retrieve the data                         |
| Clearing (Overwriting) | Moderately thorough                                                                                         | Prepares media for reuse                             | write data over the entire media                                           | Not recoverable with traditional tools               |
| Purging                | Intent is to remove all data<br><br>US GOV does not consider purging good enough for top secret information | Prepares media for reuse in less secure environmetns | Repeats the clearing process multiple times                                | Not recoverable with known technology                |
| Degaussing             | Very thorough                                                                                               | magnetic media<br><br>No plans to reuse the media    | Big Magnet                                                                 | Not recoverable                                      |
| Destruction            | Most thorough                                                                                               | Final stage int he data life cycle                   | -incineration<br>-shredding<br>-disintegration<br>-pulverizing<br>-melting | Not recoverable<br><br>Media is completely destroyed |

- Comparing Tailoring and Scoping
	- After selecting a control baseline, organizations undergo tailoring and scoping
		- This process aligns the controls in the baseline with the company's specific security requirements
		- **Tailoring**: modifying the list of security controls within a baseline to align with the org's mission
		- **Scoping**: reviewing a list of baseline security and privacy controls and selecting only those security and privacy controls taht apply to the systems you are trying to protect
- **Data Rights Management**