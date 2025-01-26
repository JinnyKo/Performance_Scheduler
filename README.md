# Performance_Scheduler

## ✨ **Project Overview**
`Performance_Scheduler` is a powerful tool designed for developers, system administrators, and engineers to:

1. **Analyze the performance of code blocks or tasks** by measuring execution time, CPU usage, GPU usage, and memory consumption.
2. **Schedule and manage tasks** efficiently using a multi-threaded scheduler.
3. Generate detailed performance reports for tasks and code execution.

Whether you’re optimizing algorithms, managing system-level tasks, or monitoring resource utilization, `Performance_Scheduler` provides actionable insights and control.

---

## 🔢 **Key Features**

### 1. **Code Performance Analysis**
- Measure the **execution time** of specific code blocks or algorithms (microsecond or nanosecond precision).
- Monitor **CPU usage** during code execution.
- Track **GPU usage** for tasks utilizing graphical processing units.
- Track **memory consumption** and detect memory-intensive operations.

### 2. **Multi-threaded Task Scheduler**
- Schedule tasks at specified intervals (e.g., every 5 seconds, once per hour).
- Run tasks **asynchronously** and manage multiple tasks simultaneously.
- Track task execution times, resource usage, and overall efficiency.

### 3. **Report Generation**
- Generate comprehensive performance reports summarizing:
  - Execution time
  - CPU, GPU, and memory usage
  - Task success/failure states
- Save reports as text or CSV files for future analysis.

### 4. **Real-time Monitoring**
- Monitor active tasks and their resource usage in real-time.
- Receive warnings if tasks exceed predefined CPU, GPU, or memory limits.

---

## 🔧 **Installation**
1. Clone this repository:
   ```bash
   git clone https://github.com/your-repo/performance_scheduler.git
   ```
2. Navigate to the project directory:
   ```bash
   cd performance_scheduler
   ```
3. Build the project using CMake (if applicable):
   ```bash
   mkdir build && cd build
   cmake ..
   make
   ```

---

## ⚙️ **Usage**

### **1. Code Performance Analysis**
Analyze the performance of a specific code block or function:
```bash
./performance_scheduler analyze_function --file=my_code.cpp --function=my_function
```
**Example Output:**
```
Execution Time: 0.123 ms
CPU Usage: 20%
GPU Usage: 15%
Memory Usage: 3.5 MB
```

### **2. Schedule a Task**
Schedule a task to run at regular intervals:
```bash
./performance_scheduler schedule_task --task=backup --interval=10s
```
**Example Output:**
```
Task: backup
Next Execution: 10s
Execution Time: 1.03 ms
CPU Usage: 10%
GPU Usage: 5%
Memory Usage: 2.5 MB
```

### **3. Generate Reports**
Generate a performance report for completed tasks:
```bash
./performance_scheduler generate_report --output=report.txt
```

### **4. Real-time Monitoring**
Monitor active tasks and their resource usage in real-time:
```bash
./performance_scheduler monitor
```
**Example Output:**
```
Current Tasks:
Task: backup | Execution Time: 1.02 ms | CPU: 10% | GPU: 5% | Memory: 2.5 MB
Task: cleanup | Execution Time: 0.5 ms | CPU: 5% | GPU: 2% | Memory: 1.2 MB
System CPU Usage: 40%
System GPU Usage: 30%
System Memory Usage: 55%
```

---

## 📊 **Features Roadmap**
- [ ] **User-defined Task Templates**: Allow users to define custom tasks and scripts.
- [ ] **GUI Support**: Integrate a graphical user interface for easier interaction.
- [ ] **Threshold-based Alerts**: Notify users when resource limits are exceeded.

---

## 🔧 **Technical Details**
- **Language**: C++
- **Standards**: C++17 or later
- **Key Libraries**:
  - `<chrono>` for time measurement
  - Multithreading (e.g., `<thread>`)
  - System APIs for CPU, GPU, and memory tracking
  - Optional: Qt or GTK for GUI (future roadmap)
  - NVIDIA NVML (for GPU usage monitoring)

---


---

## 🚀 **License**


# Performance\_Scheduler

## ✨ **프로젝트 개요**

`Performance_Scheduler`는 개발자, 시스템 관리자 및 엔지니어를 위해 설계된 강력한 도구로:

1. **코드 블록이나 작업의 성능을 분석**하여 실행 시간, CPU 사용량, GPU 사용량 및 메모리 소비를 측정합니다.
2. **작업을 효율적으로 스케줄링하고 관리**할 수 있는 멀티스레드 스케줄러를 제공합니다.
3. 작업 및 코드 실행에 대한 상세한 성능 보고서를 생성합니다.

알고리즘 최적화, 시스템 작업 관리 또는 자원 활용 모니터링에 관계없이, `Performance_Scheduler`는 실행 가능한 인사이트와 제어 기능을 제공합니다.

---

## 🔢 **주요 기능**

### 1. **코드 성능 분석**

- 특정 코드 블록 또는 알고리즘의 **실행 시간**을 마이크로초 또는 나노초 단위로 측정.
- 코드 실행 중 **CPU 사용량**을 모니터링.
- 그래픽 처리 장치를 사용하는 작업에 대한 **GPU 사용량** 추적.
- **메모리 소비량**을 추적하고 메모리 집약적 작업 감지.

### 2. **멀티스레드 작업 스케줄러**

- 특정 간격(예: 매 5초, 매 1시간)으로 작업을 스케줄링.
- 작업을 **비동기적으로 실행**하고 여러 작업을 동시에 관리.
- 작업 실행 시간, 자원 사용량 및 전체 효율성을 추적.

### 3. **보고서 생성**

- 다음 항목을 요약한 종합 성능 보고서를 생성:
  - 실행 시간
  - CPU, GPU 및 메모리 사용량
  - 작업 성공/실패 상태
- 보고서를 텍스트 또는 CSV 파일로 저장하여 향후 분석에 활용.

### 4. **실시간 모니터링**

- 활성 작업과 자원 사용량을 실시간으로 모니터링.
- 작업이 사전 정의된 CPU, GPU 또는 메모리 한도를 초과하면 경고를 수신.

---

## 🔧 **설치 방법**

1. 이 리포지토리를 클론합니다:
   ```bash
   git clone https://github.com/your-repo/performance_scheduler.git
   ```
2. 프로젝트 디렉토리로 이동:
   ```bash
   cd performance_scheduler
   ```
3. CMake를 사용하여 프로젝트 빌드(해당하는 경우):
   ```bash
   mkdir build && cd build
   cmake ..
   make
   ```

---

## ⚙️ **사용 방법**

### **1. 코드 성능 분석**

특정 코드 블록 또는 함수의 성능을 분석:

```bash
./performance_scheduler analyze_function --file=my_code.cpp --function=my_function
```

**예시 출력:**

```
Execution Time: 0.123 ms
CPU Usage: 20%
GPU Usage: 15%
Memory Usage: 3.5 MB
```

### **2. 작업 스케줄링**

정기적으로 실행되는 작업을 스케줄링:

```bash
./performance_scheduler schedule_task --task=backup --interval=10s
```

**예시 출력:**

```
Task: backup
Next Execution: 10s
Execution Time: 1.03 ms
CPU Usage: 10%
GPU Usage: 5%
Memory Usage: 2.5 MB
```

### **3. 보고서 생성**

완료된 작업에 대한 성능 보고서를 생성:

```bash
./performance_scheduler generate_report --output=report.txt
```

### **4. 실시간 모니터링**

활성 작업과 자원 사용량을 실시간으로 모니터링:

```bash
./performance_scheduler monitor
```

**예시 출력:**

```
Current Tasks:
Task: backup | Execution Time: 1.02 ms | CPU: 10% | GPU: 5% | Memory: 2.5 MB
Task: cleanup | Execution Time: 0.5 ms | CPU: 5% | GPU: 2% | Memory: 1.2 MB
System CPU Usage: 40%
System GPU Usage: 30%
System Memory Usage: 55%
```

---

## 📊 **기능 로드맵**

-

---

## 🔧 **기술 세부사항**

- **언어**: C++
- **표준**: C++17 이상
- **주요 라이브러리**:
  - `<chrono>` 시간 측정을 위해 사용
  - 멀티스레드 처리(e.g., `<thread>`)
  - CPU, GPU 및 메모리 추적을 위한 시스템 API
  - 선택 사항: GUI를 위한 Qt 또는 GTK (향후 로드맵)
  - NVIDIA NVML(GPU 사용량 모니터링용)

---

## 🛠️ **기여 가이드라인**

---





