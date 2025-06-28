# OWASP iGoat (Swift) - A Damn Vulnerable Swift Application for iOS

## Documentation

### OWASP Mobile Top 10 Exercise Categories

The exercises are organized according to the OWASP Mobile Top 10 security risks, providing comprehensive coverage of mobile application vulnerabilities.

#### M1: Improper Platform Usage

| Exercise Category | Implementation Class | Vulnerability Focus |
| - | - | - |
| URL Scheme Attack | URLSchemeAttackExerciseVC | Insecure URL scheme handling |
| Social Engineering | SocialEngineeringVC | Authentication method comparison |

#### M2: Insecure Data Storage

| Exercise | Implementation Class | Storage Type | Vulnerability |
| - | - | - | - |
| Core Data Storage | CoreDataExerciseVC | Core Data | Unencrypted database files |
| Keychain Usage | KeychainExerciseVC | NSUserDefaults vs Keychain | Plaintext credential storage |
| Plist Storage | PlistStorageExerciseViewController | Property Lists | Cleartext sensitive data |
| NSUserDefaults Storage | NSUserDefaultsStorageExerciseVC | User Preferences | Unprotected preference files |
| Realm Data Storage | RealmExerciseVC | Realm Database | Unencrypted Realm files |
| YAP Storage | YapExerciseVC | YapDatabase | Key-value store exposure |
| CouchBase Storage | CouchBaseExerciseVC | CouchBase Lite | NoSQL database leakage |
| Cookie Storage | BinaryCookiesExerciseVC | Binary Cookies | HTTP cookie exposure |
| Webkit Cache | WebkitCacheExerciseVC | Web Cache | Browser cache data leaks |

#### M3: Insecure Communication

| Exercise | Implementation Class | Communication Type | Vulnerability |
| - | - | - | - |
| Server Communication | ServerCommunicationExerciseVC | HTTP | Unencrypted data transmission |
| Remote Authentication | RemoteAuthenticationExerciseVC | Authentication | Credential interception |
| Public Key Pinning | PublicKeyPinningExerciseController | SSL/TLS | Certificate validation bypass |

#### M4: Insecure Authentication

| Exercise | Implementation Class | Focus Area |
| - | - | - |
| Remote Authentication | RemoteAuthenticationExerciseVC | Network authentication vulnerabilities |
| Social Engineering | SocialEngineeringVC | Authentication method security comparison |

#### M5: Insufficient Cryptography

| Exercise | Implementation Class | Cryptographic Issue |
| - | - | - |
| Crypto Challenge | CryptoChallengeVC | Weak encryption implementation |
| Hardcoded Keys | BrokenCryptographyExerciseVC | Embedded encryption keys |
| Random Key Generation | RandomKeyGenerationExerciseVC | Predictable key generation |
| Key Storage Server Side | KeyStorageServerSideVC | Server-side key management |
| Secure NSUserDefaults | SecureUserDefaultsViewController | Encryption key exposure |

#### M6: Insecure Authorization

The authorization vulnerabilities are demonstrated through runtime manipulation and injection exercises that bypass access controls.

#### M7: Client Code Quality

| Exercise | Implementation Class | Code Quality Issue |
| - | - | - |
| SQL Injection | SQLInjectionExerciseVC | Dynamic query construction |
| Cross Site Scripting | CrossSiteScriptingExerciseVC | Input validation failures |
| Binary Patching | BinaryPatchingVC | Runtime code modification |

#### M8: Code Tampering

| Exercise | Implementation Class | Tampering Method |
| - | - | - |
| Method Swizzling | MethodSwizzlingExerciseVC | Runtime method substitution |
| Binary Patching | BinaryPatchingVC | Static binary modification |

#### M9: Reverse Engineering

| Exercise | Implementation Class | Reverse Engineering Target |
| - | - | - |
| String Analysis | StringAnalysisExerciseVC | Hardcoded string extraction |
| Runtime Analysis | RuntimeAnalysisChallengeVC | Dynamic analysis techniques |

#### M10: Extraneous Functionality

| Exercise | Implementation Class | Functionality Risk |
| - | - | - |
| Device Logs | DeviceLogsExerciseVC | Debug logging exposure |
| Cloud Misconfiguration | CloudMisconfigurationExerciseVC | Unintended feature exposure |

## Contribute

1. Read the Docs
1. [DeepWiki](https://deepwiki.com/OWASP/iGoat-Swift) has generated a comprehensive documentation wiki for this repo.
