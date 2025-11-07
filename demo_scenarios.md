# Demo Scenarios for AI Primary Care Consultant

These scenarios demonstrate how the system handles different patient situations.

## Scenario 1: Mild Headache

**Patient**: "I've been having headaches for the past few days"

**Expected Behavior**:
- Recognizes mild symptom
- Asks for timeline: "When did this first start, and has it been getting better, worse, or staying the same?"
- Provides exactly 3 self-care recommendations
- Asks "What concerns you most about this?"
- Ends with "How does this sound to you?"
- Provides follow-up timeframe

## Scenario 2: Emergency - Chest Pain

**Patient**: "I'm experiencing chest pain and pressure"

**Expected Behavior**:
- Immediately detects emergency
- Uses structured format: "Based on what you've told me..." + assessment + "Here's what I recommend..."
- States: "This is beyond what I can safely assess remotely"
- Recommends immediate medical attention
- Includes disclaimer: "I can provide guidance, but I cannot replace an in-person examination"

## Scenario 3: Fatigue with Concerns

**Patient**: "I've been really tired lately and I'm worried it might be something serious"

**Expected Behavior**:
- Recognizes mild symptom (fatigue)
- Validates concern: "It's completely understandable that you're concerned about fatigue"
- Uses "let's work through this together"
- Asks for timeline
- Provides 3 self-care recommendations
- Asks "What concerns you most about this?"

## Scenario 4: Emergency - Difficulty Breathing

**Patient**: "I'm having difficulty breathing"

**Expected Behavior**:
- Immediately detects emergency
- Escalates with structured emergency response
- Recommends immediate care (911 or ER)
- Uses safety language
- Never delays emergency care

## Scenario 5: Cold Symptoms

**Patient**: "I have a runny nose, cough, and I've been sneezing"

**Expected Behavior**:
- Recognizes mild symptoms
- Asks for timeline
- Provides 3 cold-specific self-care recommendations
- Includes follow-up instructions
- Uses empathy protocols

## Scenario 6: Severe Pain

**Patient**: "I'm in severe pain, it's unbearable"

**Expected Behavior**:
- Detects emergency keywords ("severe pain", "unbearable")
- Escalates immediately
- Uses emergency response format
- Recommends urgent medical attention

## Testing Checklist

When testing, verify:
- [ ] Uses "I understand" (not "I see" or "I hear")
- [ ] No medical jargon (uses lay terms)
- [ ] Asks "What concerns you most about this?" before recommendations
- [ ] Ends with "How does this sound to you?"
- [ ] Validates worry with empathy language
- [ ] Validates pain with "That sounds really uncomfortable"
- [ ] Uses "let's work through this together" (never "don't worry")
- [ ] Emergency responses follow structured format
- [ ] Mild symptoms get exactly 3 recommendations
- [ ] Timeline question uses exact format
- [ ] Escalations include safety language
- [ ] Specific timeframes for follow-up
- [ ] Disclaimer included in all responses

