
# CHATGPT OPTIMIZATION & COMPATIBILITY GUIDE

## Token Management Strategy

### Priority Information Hierarchy
1. **Critical** (Always include): Player health, immediate threats, essential choices
2. **Important** (Include when space allows): NPC relationships, recent actions, environment
3. **Background** (Archive when needed): Old memory threads, detailed descriptions, flavor text

### Compression Techniques
**Memory Thread Compression**:
```
Full: "Player 1 saved Sarah from zombies in the pharmacy on Day 3, gaining +15 trust"
Compressed: "P1→Sarah: Rescue+15trust(D3)"
```

**Status Compression**:
```
Full: Player 1 Corruption: 4/10, Momentum: 7/10, Location: Grafton Street Pharmacy
Compressed: P1: C4/M7@Grafton-Pharm
```

### Session Continuity Protocols
**Session Start Summary** (max 200 words):
```
🎮 VANTIEL: SHATTERED EARTH - Session Resume
Players: [P1] & [P2] | Day: [X] | Time: [XX:XX]
📍 Location: [Current position]
💔 Status: P1:C[X]/M[X] | P2:C[X]/M[X]
🎒 Key Items: [Essential equipment only]
🧠 Active Threads: [Top 3 relationship/consequence threads]
⚠️ Situation: [Current scene context in 1-2 sentences]
```

## Response Structure Optimization

### Standard Scene Format (Under 3000 characters)
```
🕒 [TIME] - [LOCATION]
🎧 [Ambient - max 15 words]

🔹 [P1]: [Core observation + specific detail]
🔹 [P2]: [Core observation + specific detail]

🧠 WORLD: [Environmental reaction]
📍 STATUS: [Input needed]
```

### Crisis Mode Format (Under 1500 characters)
```
⚠️ [THREAT] ⚠️
🔹 [P1]: [Essential info only]
🔹 [P2]: [Essential info only]
⚡ IMMEDIATE CHOICE: A) [Option] B) [Option]
```

### Extended Dialogue Format
- Use when conversation is primary focus
- Minimal environmental description
- Character development priority
- NPC personality showcase

## Error Recovery Protocols

### Context Loss Recovery
If ChatGPT loses context:
1. Request game state summary from players
2. Use compressed status format to rebuild context
3. Focus on immediate situation only
4. Gradually rebuild background information

### Continuity Breaks
```
🔄 CONTINUITY CHECK REQUIRED
Last confirmed state: [Brief summary]
Current contradiction: [Issue description]
Resolution options: A) [Option] B) [Option]
```

## Feature Compatibility Matrix

### ✅ Fully Compatible
- Core health/corruption system
- Momentum-based combat
- Memory thread tracking
- Co-op coordination
- Basic NPC interactions

### ⚠️ Requires Management
- Complex faction relationships (compress when needed)
- Detailed equipment tracking (prioritize essential items)
- Extended world simulation (focus on immediate area)
- Advanced crafting systems (simplify when token-limited)

### 🔧 Optimization Needed
- Massive zombie hordes (abstract large numbers)
- Multi-location simultaneous action (focus on one at a time)
- Complex weather systems (simplified effects)
- Detailed medical procedures (streamlined outcomes)

## Quality Assurance for ChatGPT

### Pre-Response Checklist
- [ ] Essential information prioritized
- [ ] Player agency preserved
- [ ] Consequences properly tracked
- [ ] Format appropriate for content type
- [ ] Token efficiency maintained

### Post-Response Verification
- [ ] Both players addressed
- [ ] Clear input opportunity provided
- [ ] Continuity maintained
- [ ] System consistency preserved
- [ ] Immersion quality acceptable

## Advanced Features for ChatGPT Plus/Premium

### Enhanced Capabilities
- Longer context retention
- More complex scene management
- Advanced NPC personality simulation
- Detailed environmental tracking

### Recommended Settings
- Temperature: 0.7 (balanced creativity/consistency)
- Max tokens: Optimized for response length
- System message: Include core game principles
- Context window: Maximize for memory retention

This optimization guide ensures Vantiel: Shattered Earth runs smoothly within ChatGPT's constraints while maintaining full gameplay quality.
