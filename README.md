# Virtual CPU - Instruction Cycle Simulator

## Assignment Deliverables (GET211 GROUP 14)

### Files Included:
1. **GET211 GROUP14 (1)_024555.html** - Modified CPU simulator (main deliverable)
2. **test_program_1_arithmetic.txt** - Test program for ALU operations
3. **test_program_2_addressing.txt** - Test program for addressing modes
4. **test_program_3_branching.txt** - Test program for conditional branching
5. **TECHNICAL_REPORT.txt** - Technical documentation (1450 words)
6. **Project_brief1.pdf** - Original assignment brief

## Features Implemented:

### New ALU Instructions (25 marks):
- ✅ SUB (Subtract)
- ✅ MUL (Multiply)
- ✅ DIV (Divide with zero protection)
- ✅ AND (Bitwise AND)
- ✅ OR (Bitwise OR)
- ✅ NOT (Bitwise NOT)

### Addressing Modes (25 marks):
- ✅ Immediate addressing: `LOAD R1, #100`
- ✅ Direct memory: `LOAD R1, 500`
- ✅ Register-indirect: `LOAD R1, (R2)`
- ✅ Indexed addressing: `LOAD R1, 50(R2)`

### Control Flow (15 marks):
- ✅ JNZ (Jump if Not Zero) instruction
- ✅ Z flag implementation and display
- ✅ Conditional branch logic

### Code Quality (15 marks):
- ✅ Bug fixes (critical switch statement fix)
- ✅ Comprehensive comments
- ✅ Error handling
- ✅ Clean code structure

### Test Programs (10 marks):
- ✅ Three comprehensive test programs
- ✅ Expected results documented
- ✅ All features demonstrated

### Technical Report (10 marks):
- ✅ 1450-word technical report
- ✅ Implementation details
- ✅ Design decisions explained
- ✅ Testing methodology

## Critical Bugs Fixed:

1. **Switch statement fatal flaw** - Default case was in middle, making ALU instructions unreachable
2. **Missing JNZ in UI** - Added to supported opcodes list
3. **Incomplete getValue()** - Extended to support all addressing modes in ALU operations
4. **Missing Z flag display** - Added to state grid for visibility

## How to Use:

1. Open `GET211 GROUP14 (1)_024555.html` in any modern web browser
2. Edit instruction memory (left panel) or use test programs
3. Click "Apply / Reset CPU" to load the program
4. Use "Step Phase" to walk through Fetch → Decode → Execute
5. Or use "Step Full Instruction" or "Run Until End"
6. Watch the CPU state update in real-time

## Test Programs:

Copy the instruction sequences from the test program files into the simulator:
- **Test 1**: Demonstrates all ALU operations with immediate addressing
- **Test 2**: Shows register-indirect and indexed addressing modes
- **Test 3**: Implements a countdown loop using JNZ conditional branch

## Submission Date:
January 5, 2026 (Due Date Met)