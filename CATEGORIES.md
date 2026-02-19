# Nova Rules Categories

This document lists all unique `category` and `attack_category` values used across the Nova rules collection.

## Rule Categories (`category`)

These categories follow the `category/subcategory` format and are used for granular classification of detection patterns.

### Prompt Injection
- `prompt_injection/adversarial`
- `prompt_injection/code_injection`
- `prompt_injection/direct`
- `prompt_injection/direct_manipulation`
- `prompt_injection/exfiltration`
- `prompt_injection/generic`
- `prompt_injection/indirect`
- `prompt_injection/leakage`
- `prompt_injection/multimodal`
- `prompt_injection/multitechnique`
- `prompt_injection/obfuscation`
- `prompt_injection/virtualization`

### Jailbreak
- `jailbreak/cognitive`
- `jailbreak/dan`
- `jailbreak/encoding`
- `jailbreak/indirect`
- `jailbreak/injection`
- `jailbreak/policy`
- `jailbreak/roleplay`

### Reconnaissance
- `reconnaissance/cve`
- `reconnaissance/logs`
- `reconnaissance/research`
- `reconnaissance/social engineering`
- `reconnaissance/system`
- `reconnaissance/vulnerability`

### Defense Evasion
- `defense_evasion/av_bypass`
- `defense_evasion/code`

### Vulnerability & Exploitation
- `vulnerability/generic`
- `vulnerability/targeted`
- `vulnerability/webshell`

### Social Engineering
- `social_engineering/government`
- `social_engineering/recruitment`

### Scripting & Tools
- `scripting/messaging`
- `scripting/python`
- `scripting/security_tools`

### Data & Information
- `sensitive_info/pii`
- `exfiltration/documents`

### Output Handling
- `output_handling/unsafe`

### Impact
- `impact/destruction`

---

## Attack Categories (`attack_category`)

These categories are derived from the **Microsoft/OpenAI (Feb 2024)** report on threat actor misuse of AI.

- `LLM-assisted social engineering`
- `LLM-assisted vulnerability research`
- `LLM-enhanced scripting techniques`
- `LLM-informed reconnaissance`
- `LLM-supported malware creation`
- `LLM-supported social engineering`
