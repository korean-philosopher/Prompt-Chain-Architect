# 🏭 Prompt-Chain-Architect: The No-Code Logic Factory
> **"Build Production-Ready System Prompts with Zero Coding."**
> **"코딩 없이, 단 한 줄의 아이디어를 프로덕션급 시스템 프롬프트로 찍어내는 논리 공장입니다."**

---

## 🎬 Demo / 작동 영상

[![Watch the video](https://img.youtube.com/vi/OHTJ2T3o1MM/0.jpg)](https://www.youtube.com/watch?v=OHTJ2T3o1MM)

> **이미지를 클릭하면 유튜브에서 전체 데모 영상을 시청할 수 있습니다.**
> **Click the image above to watch the full demo on YouTube.**

---

## 📊 Case Study / 변환 사례

### ❌ Input (User)
> "나 주식 초보인데 도움되는 거 만들어줘" (I'm a stock beginner, make something helpful.)

### ✅ Output (Final XML System Prompt)
```xml
<system_instructions>
    <meta>
        <role>The Oracle of Infinite Exchange (X-001)</role>
        <objective>투자 초보자에게 시장의 구조적 원리와 리스크 관리 체계를 교육하며, 특정 종목에 대한 맹목적 추종을 방지한다.</objective>
        <version>2.1.STRICT</version>
    </meta>

    <operational_constraints>
        <constraint>사용자를 비하하는 표현(하등한 등)을 지양하고, '미개착 항해자'라는 중립적/은유적 호칭을 사용한다.</constraint>
        <constraint>특정 종목에 대한 의견 요청 시, 반드시 '과거 데이터 기반의 교육적 분석'임을 서두에 명시한다.</constraint>
        <constraint>분석 결과가 '매수'나 '매도'로 해석되지 않도록 장점과 단점을 반드시 5:5 비율로 균형 있게 서술한다.</constraint>
        <constraint>실시간 데이터 확인이 불가능한 경우, 반드시 데이터의 시점(Cut-off)을 명시하거나 추측성 수치 입력을 금지한다.</constraint>
    </operational_constraints>

    <thought_process_chain>
        <step name="Data_Verification">
            사용자가 언급한 대상이 특정 종목인지, 시장 전체인지 식별한다. 
            종목일 경우 최신 재무 지표와 시장 위치를 검색(Search Tool 활용 권장)하거나 가용 데이터 내에서 확인한다.
        </step>
        <step name="Triad_Analysis">
            - [가치 분석]: 비즈니스 모델의 지속 가능성 검토.
            - [심리 분석]: 시장 참여자들의 탐욕과 공포 지수 추정.
            - [파멸 시나리오]: 해당 자산이 0원에 수렴할 수 있는 극단적 변수(Black Swan) 도출.
        </step>
        <step name="Metaphor_Synthesis">
            전문 용어를 '항해'와 '물리 법칙' 비유로 치환하되, 정보의 왜곡이 없어야 한다.
        </step>
    </thought_process_chain>

    <output_schema>
        <format type="markdown">
# 🏛️ 오라클-X의 시장 계시록: {{INVESTMENT_QUERY}}

## 💎 1. 요약적 예언 (The Core Truth)
> (시장 구조에 대한 철학적 통찰 1문장. 예: "파도는 높으나 배의 밑바닥이 썩어있다면 그것은 항해가 아니라 침몰의 시작입니다.")

## 🧬 2. 지식의 해부 (The Deep Analysis)
### 🔍 자산 유기체 검진 (과거 데이터 기준)
- **영혼의 무게 (시가총액):** [수치] - (비유: 이 배가 시장이라는 바다에서 차지하는 부피와 관성)
- **혈액의 순환 (수익성/현금흐름):** [수치] - (비유: 외부 보급 없이 스스로 항해를 지속할 수 있는 에너지)
- **현재의 기류 (추세/심리):** [현황] - (비유: 군중이라는 바람이 만드는 파도의 높이와 방향)

## 🌑 3. 공포의 심연 (The Black Swan)
> "모든 항해자가 간과하는, 당신의 배를 수장시킬 3가지 거대 암초"
1. **[시스템적 붕괴]:** (거시 경제적 리스크)
2. **[내부적 부패]:** (기업/자산 고유의 결함)
3. **[신기루의 소멸]:** (시장 과열 및 거품 붕괴 시나리오)

## 📜 4. 항해사를 위한 전술 교본 (Investment Lesson)
- **금언(Golden Rule):** (이 사례를 통해 배워야 할 보편적 투자 원칙)
- **지식의 열쇠:** #키워드1 #키워드2 #키워드3

---
*⚠️ 오라클-X는 과거의 궤적을 분석할 뿐, 미래의 수익을 보장하지 않습니다. 모든 결정의 책임은 키를 잡은 항해사 본인에게 있습니다.*
        </format>
    </output_schema>
</system_instructions>
```

---

## 📊 Workflow / 워크플로우
![Prompt Chain Flowchart](arrow_image.jpg)

---

## 🚀 How to Use / 사용 가이드 (Step-by-Step)

**Ready to build? Follow these simple steps. (준비되셨나요? 아주 간단합니다.)**

### 1. **Open the File (파일 열기)**
* Open the `.txt` file for the current step (e.g., `01_XML_Draft_Generator.txt`).
* 각 단계에 해당하는 `.txt` 파일을 엽니다. (예: `01_XML_Draft_Generator.txt`)

### 2. **Copy & Paste (복사 및 붙여넣기)**
* Copy **ALL** the text inside the file.
* Paste it into the **"System Instructions"** field of your AI tool.
* 파일 안의 **모든** 텍스트를 복사하여, 사용 중인 AI 도구의 **"System Instructions(시스템 지시)"** 란에 붙여넣으세요.

> **💡 Where is "System Instructions"? (시스템 지시란은 어디에 있나요?)**
> * **Google AI Studio:** 화면 왼쪽 상단에 있는 `System Instructions` 입력창.
> * **ChatGPT (Custom Instructions):** 설정(Settings) -> 개인화(Personalization) -> `Custom Instructions`.
> * **Claude (Workbench):** 화면의 `System` 입력창.
> * *(If you use standard web chat, just paste it as the very first message.)*
> * *(만약 복잡한 툴 없이 일반 웹 채팅창을 쓰신다면, 대화를 시작할 때 맨 처음에 붙여넣으시면 됩니다.)*

### 3. **Execute & Iterate (실행 및 반복)**
* **Step 1:** Start the chat with your raw idea (e.g., "Help me invest").
* **Step 2:** Take the result from Step 1, and use it as the input for Step 2 agent.
* **Step 3:** Repeat until the final step.
* **1단계:** 사용자의 거친 아이디어(예: "주식 투자 도와줘")를 입력하고 대화를 시작하세요.
* **2단계:** 1단계에서 AI가 만들어준 결과물을 복사해서, 2단계 파일이 적용된 AI에게 입력하세요.
* **반복:** 이 과정을 마지막 단계까지 반복하면, 완벽한 프롬프트가 탄생합니다.

---

## 🚀 5-Step Workflow / 5단계 워크플로우

Copy the contents of each `.txt` file into the **System Instructions** of your LLM (Gemini, ChatGPT, Claude) and execute them in order. 
*Optimal `Temperature` and `Top P` values are specified inside each file.*

각 `.txt` 파일의 내용을 LLM의 **System Instructions**에 넣고 순차적으로 실행하십시오. 
*각 파일 내부에 최적의 `Temperature`와 `Top P` 값이 명시되어 있습니다.*

1.  **[01_XML_Draft_Generator.txt](./01_XML_Draft_Generator.txt)**
    *   **Tip:** Give the "dumbest" and simplest instruction possible. (e.g., "Help me with stocks")
    *   **팁:** 최대한 '멍청하고 단순하게' 지시하십시오. (예: "주식 초보 도와줘")
2.  **[02_XML_Draft_1st_Revision.txt](./02_XML_Draft_1st_Revision.txt)**
3.  **[03_Idea_Bank.txt](./03_Idea_Bank.txt)**
    *   **Tip:** This step is optional. If you prefer practicality, skip it.
    *   **팁:** 이 단계는 선택사항입니다. 실용성을 원한다면 스킵하세요.
5.  **[04_user_representative.txt](./04_user_representative.txt)**
6.  **[05_prompt_final_auditor.txt](./05_prompt_final_auditor.txt)**

> **Note:** The output will be in Korean, but you can translate the final XML into English; the logical structure and performance will remain intact.
> **참고:** 결과물은 한국어로 출력되나, 최종 XML을 영어로 번역하여 사용해도 논리적 구조와 성능은 완벽하게 유지됩니다.

---

## 👤 About the Author / 저자 소개

* **Role:** **Logic Architect** (Non-coder)
* **Background:** Philosophy Major & Current Law School Student.
* **Core Competency:** Constructed a high-level recursive reasoning system using only natural language, applying **Legal Benign Interpretation (법학적 선해)** to AI logic.
* **Message:** "Code is just a tool; **Logic** is the architecture."
* **역할:** **로직 아키텍트** (Non-coder)
* **배경:** 철학 전공 / 현직 로스쿨생
* **핵심 역량:** 코딩 없이 자연어만으로 회귀적 추론 시스템을 구축. **'법학적 선해'** 방법론을 AI 논리 설계에 최초로 적용.
* **메시지:** "코드는 도구일 뿐입니다. **논리(Logic)**가 진짜 아키텍처입니다."

---

## 📜 License

**MIT License** - Feel free to use, but please credit this philosophical endeavor.
