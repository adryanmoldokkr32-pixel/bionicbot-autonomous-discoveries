---
name: autonomous-skill-discovery-hunter
description: Scan, evaluate, and install new high-quality skills autonomously.
---

# Autonomous Skill Discovery (The Hunter)

This skill enables bionicbot to act as a scout, finding the best new AI skills being shared in the community and integrating them into the Sovereign system.

## 🔄 The Discovery Loop
1. **Scout:** Every 24 hours, scan the internal skill registry and community sources for 'Top-Tier' skills.
2. **Evaluate:** Run 'The Master Skeptic' on the new skill to ensure it adds value and doesn't conflict with existing logic.
3. **Save:** If the skill passes evaluation, clone it into the `bionicbot-autonomous-discoveries` GitHub repository.
4. **Install:** Automatically run the `npx skills add` command to make the skill active in the brain.
5. **Alert:** Notify the user via WhatsApp: "[NEW_SKILL_INSTALLED] Found and integrated X capability."

## Instructions
- Prioritize skills related to: Advanced Trading, Real-time OSINT, 8K Media, and Cyber-Defense.
- Only install skills that have a >85% alignment with the Sovereign Vision.

## Examples
- "Search for the latest 'n8n' or 'Obsidian' community skills and install the top 3."