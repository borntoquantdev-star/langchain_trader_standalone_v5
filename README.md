# 📓 LangChain SMC Trading Agent — Standalone

**ไม่ต้องรัน Backend** — ทุกอย่างทำใน Notebook โดยตรง!

---

## 🗂️ ลำดับเรียน (5 หน่วย)

### 📘 หน่วยที่ 1 — LLM คืออะไร (เริ่มที่นี่!)
| ไฟล์ | เนื้อหา |
|------|---------|
| `unit1_llm_basics.ipynb` | LLM, LangChain, Prompt, Temperature, Chat History |

### 📗 หน่วยที่ 2 — LLM กับการเทรดเบื้องต้น
| ไฟล์ | เนื้อหา |
|------|---------|
| `unit2_llm_trading.ipynb` | วิเคราะห์ราคา, Candlestick, แนวรับ/ต้าน |

### ⛓️ หน่วยที่ 3 — Chain (LCEL)
| ไฟล์ | เนื้อหา |
|------|---------|
| `unit3_chains.ipynb` | `prompt \| llm \| parser`, PromptTemplate, OutputParser, Trading Chain |

### 📙 หน่วยที่ 4 — Tools & Agents
| ไฟล์ | เนื้อหา |
|------|---------|
| `unit4_tools_agents.ipynb` | `@tool`, `bind_tools`, `AgentExecutor` |

### 📕 หน่วยที่ 5 — Full SMC Trading Agent
| # | ไฟล์ | เนื้อหา |
|---|------|---------|
| 1 | `01_mt5_data_and_smc.ipynb` | ดึง MT5 + SMC indicators + กราฟ |
| 2 | `02_smc_indicators_explained.ipynb` | FVG, BOS, OB, Liquidity |
| 3 | `03_llm_analysis.ipynb` | GPT-4o + Vision |
| 4 | `04_agent_with_tools.ipynb` | Agent + Tools |
| 5 | `05_full_trading_agent.ipynb` | Top-Down + Chat + Auto Loop |

> **เรียนตามลำดับ** หน่วย 1 → 2 → 3 → 4 → 5

---

## 🔧 การติดตั้ง

```bash
pip install -r requirements.txt
cp .env.example .env   # ใส่ OPENAI_API_KEY
jupyter notebook
```

> ⚠️ หน่วย 1-4 ต้องการแค่ `OPENAI_API_KEY` | หน่วย 5 ต้องการ MT5 หรือ CSV

## ⚠️ คำเตือน

> ผลวิเคราะห์จาก AI **ไม่ใช่คำแนะนำทางการเงิน** — ใช้เพื่อการศึกษาเท่านั้น
