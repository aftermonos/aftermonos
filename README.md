<!-- ======================================================================= -->
<!--                         aftermonos // README.md                          -->
<!--                  built different. compiled with -O3.                     -->
<!-- ======================================================================= -->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,50:1a2b00,100:76B900&height=240&section=header&text=aftermonous&fontSize=76&fontColor=FFFFFF&fontAlignY=36&desc=ideate()%20%20build()%20%20iterate()%20%20repeat()&descSize=18&descAlignY=58&descColor=76B900&animation=fadeIn" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/aftermonos">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3000&pause=800&color=76B900&center=true&vCenter=true&width=760&lines=%3E+initializing+aftermonos.exe;%3E+NVIDIA+Intern+%7C+2024+-+2026;%3E+GPUs%2C+systems%2C+AI%2C+and+everything+in+between;%3E+just+making+stuff+i+think+is+cool;%3E+compiling+ideas+into+reality;%3E+profiling+my+own+life+in+Nsight;%3E+accelerated+by+curiosity" alt="typing" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/NVIDIA-Intern%202024%20--%202026-76B900?style=for-the-badge&logo=nvidia&logoColor=white&labelColor=000000" />
  <img src="https://img.shields.io/badge/Based%20in-San%20Francisco-76B900?style=for-the-badge&labelColor=000000" />
  <img src="https://img.shields.io/badge/Status-Building-76B900?style=for-the-badge&labelColor=000000" />
  <img src="https://img.shields.io/badge/Mode-Full%20Stack%20to%20Full%20Silicon-76B900?style=for-the-badge&labelColor=000000" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=aftermonos&color=76B900&style=flat-square&label=PROFILE+VIEWS" />
  <a href="https://x.com/aftermonous"><img src="https://img.shields.io/badge/X-@aftermonous-000000?style=flat-square&logo=x&logoColor=white" /></a>
  <img src="https://img.shields.io/github/followers/aftermonos?label=FOLLOWERS&style=flat-square&color=76B900&labelColor=000000" />
  <img src="https://img.shields.io/badge/Coffee-Saturated-76B900?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Sleep-Deprecated-red?style=flat-square&labelColor=000000" />
</p>

<br/>

```text
     _    _____ _____ _____ ____  __  __  ___  _   _  ___  _   _ ____
    / \  |  ___|_   _| ____|  _ \|  \/  |/ _ \| \ | |/ _ \| | | / ___|
   / _ \ | |_    | | |  _| | |_) | |\/| | | | |  \| | | | | | | \___ \
  / ___ \|  _|   | | | |___|  _ <| |  | | |_| | |\  | |_| | |_| |___) |
 /_/   \_\_|     |_| |_____|_| \_\_|  |_|\___/|_| \_|\___/ \___/|____/

 [ accelerated computing ]  [ systems ]  [ machine learning ]  [ graphics ]
```

<br/>

```text
aftermonos@nvidia:~$ nvidia-smi
+-----------------------------------------------------------------------------------------+
| NVIDIA-SMI 2026.10         Driver Version: curiosity       CUDA Version: always_latest  |
|-----------------------------------------+------------------------+----------------------|
| GPU  Name                 Persistence-M | Bus-Id          Disp.A | Volatile Uncorr. ECC |
| Fan  Temp   Perf          Pwr:Usage/Cap |           Memory-Usage | GPU-Util  Compute M. |
|=========================================+========================+======================|
|   0  aftermonos                      On |   00000000:SF:00.0  On |                  N/A |
| MAX   42C    P0           ideas / inf W |     2026MiB / inf MiB  |    100%      Default |
+-----------------------------------------+------------------------+----------------------+
|   1  side_projects                   On |   00000000:SF:01.0 Off |                  N/A |
| MAX   88C    P0          always / inf W |    9999MiB / inf MiB  |    100%      Default |
+-----------------------------------------+------------------------+----------------------+

+-----------------------------------------------------------------------------------------+
| Processes:                                                                              |
|  GPU   PID    Type   Process name                                          GPU Memory   |
|=========================================================================================|
|    0   2024    C     ./ideate                                                  512MiB   |
|    0   2025    C     ./build                                                  1024MiB   |
|    0   2025    C     ./iterate                                                 768MiB   |
|    0   2026    C     ./repeat                                                  inf MiB  |
|    1   ----    C     ./train --model=everything --epochs=forever              8192MiB   |
|    1   ----    G     ./ship_cool_stuff                                     always on    |
+-----------------------------------------------------------------------------------------+
```

<br/>

## `> whoami`

```python
from dataclasses import dataclass, field


@dataclass
class Aftermonous:
    """just making stuff i think is cool."""

    handle:    str   = "aftermonos"
    role:      str   = "Intern @ NVIDIA"
    tenure:    tuple = (2024, 2026)
    location:  str   = "San Francisco, CA"
    mindset:   str   = "if it seems cool, build it. if it works, make it faster."
    core_loop: list  = field(default_factory=lambda: ["ideate()", "build()", "iterate()", "repeat()"])

    domains: dict = field(default_factory=lambda: {
        "compute":   ["CUDA", "C++", "kernel optimization", "parallel algorithms"],
        "ai":        ["PyTorch", "training pipelines", "inference", "LLMs"],
        "systems":   ["Linux", "distributed systems", "profiling", "performance tuning"],
        "graphics":  ["real time rendering", "shaders", "simulation"],
        "product":   ["full stack web", "tooling", "making things look clean"],
    })

    socials: dict = field(default_factory=lambda: {
        "x":      "x.com/aftermonous",
        "github": "github.com/aftermonos",
    })

    def __iter__(self):
        while True:
            yield from self.core_loop

    def __repr__(self):
        return f"<{self.handle} | {self.role} | {self.tenure[0]} - {self.tenure[1]}>"


if __name__ == "__main__":
    me = Aftermonous()
    print(me)
    for step in me:
        print(f"[running] {step}")
```

<br/>

## `> boot.log`

```diff
+ [  OK  ] Mounted /dev/curiosity
+ [  OK  ] Loaded kernel module: cuda
+ [  OK  ] Loaded kernel module: tensor_cores
+ [  OK  ] Loaded kernel module: nccl
+ [  OK  ] Loaded kernel module: cudnn
+ [  OK  ] Started service: side-projects.service
+ [  OK  ] Started service: deep-work.service
+ [  OK  ] Reached target: NVIDIA Internship (2024 - 2026)
+ [  OK  ] Established uplink to San Francisco
+ [  OK  ] Synced 34 following, 26 followers
! [ WARN ] Coffee levels below recommended threshold
! [ WARN ] Number of open tabs exceeds sane limits
! [ WARN ] 47 unfinished side projects detected, launching 48th anyway
- [ FAIL ] sleep.service could not be started: ideas still running
- [ FAIL ] touch_grass.service timed out after 2026 ms
+ [  OK  ] System ready. Welcome back, aftermonous.
```

<br/>

## `> git log --oneline career`

```text
* 2026  HEAD -> main     still building. still shipping. still curious.
* 2026  feat:            leveled up on GPU performance engineering
* 2025  feat:            shipped real work at NVIDIA scale
* 2025  perf:            learned that every microsecond has a story
* 2025  refactor:        rewrote my mental model of how computers actually work
* 2024  feat:            joined NVIDIA as an intern
* 2024  init:            started making stuff i think is cool
* ----  root commit:     wrote hello world and never looked back
```

<br/>

## `> kernel.cu`

```cpp
#include <cuda_runtime.h>
#include "ideas.h"

// one thread per idea. no idea left behind.
template <int ITERATIONS>
__global__ void make_cool_stuff(const Idea* __restrict__ ideas,
                                Project*    __restrict__ out,
                                int n)
{
    __shared__ Inspiration tile[256];

    int i = blockIdx.x * blockDim.x + threadIdx.x;
    if (i >= n) return;

    tile[threadIdx.x] = load_inspiration(ideas[i]);
    __syncthreads();

    Project p = build(tile[threadIdx.x]);

    #pragma unroll
    for (int pass = 0; pass < ITERATIONS; ++pass)
        p = iterate(p);

    out[i] = ship(p);
}

int main()
{
    constexpr int threads = 256;
    const     int blocks  = (ideas.size() + threads - 1) / threads;

    cudaStream_t stream;
    cudaStreamCreate(&stream);

    make_cool_stuff<16><<<blocks, threads, 0, stream>>>(brain, github, ideas.size());

    cudaStreamSynchronize(stream);   // wait for the world to catch up
    cudaStreamDestroy(stream);
    return 0;
}
```

<br/>

## `> train.py`

```python
import torch
import torch.nn as nn
from torch.cuda.amp import autocast, GradScaler

class Brain(nn.Module):
    def __init__(self):
        super().__init__()
        self.curiosity = nn.Linear(4096, 4096)
        self.skill     = nn.TransformerEncoder(
            nn.TransformerEncoderLayer(d_model=4096, nhead=32), num_layers=96
        )
        self.output    = nn.Linear(4096, 1)   # 1 = shipped

    def forward(self, x):
        return self.output(self.skill(self.curiosity(x)))


model  = Brain().cuda()
model  = torch.compile(model)
opt    = torch.optim.AdamW(model.parameters(), lr=3e-4)
scaler = GradScaler()

for epoch in range(2024, 2027):
    for batch in problems_worth_solving:
        with autocast(dtype=torch.bfloat16):
            loss = model(batch).mean()
        scaler.scale(loss).backward()
        scaler.step(opt)
        scaler.update()
        opt.zero_grad(set_to_none=True)
    print(f"[epoch {epoch}] loss trending down, skills trending up")
```

<br/>

## `> pipeline`

```text
   +----------+     +-------------+     +-----------+     +------------+     +--------+
   |   idea   | --> |  prototype  | --> |  profile  | --> |  optimize  | --> |  ship  |
   +----------+     +-------------+     +-----------+     +------------+     +--------+
        ^                                     |                                   |
        |                                     v                                   |
        |                              +-------------+                            |
        |                              |   nsight    |                            |
        |                              |  says no.   |                            |
        |                              +-------------+                            |
        |                                                                         |
        +--------------------------------- repeat() <-----------------------------+

   latency: low        throughput: high        bottleneck: hours in a day
```

<br/>

## `> nsys profile ./aftermonos`

```text
 CUDA API Statistics:

 Time (%)   Total Time (ns)   Num Calls   Name
 --------   ---------------   ---------   -------------------------------------
     38.4      9,999,999,999       2,024  thinkAboutProblem
     24.1      6,275,000,000       2,025  writeCode
     17.6      4,580,000,000       2,026  debugAt3AM
     11.2      2,915,000,000       1,337  optimizeUntilItFlies
      6.3      1,640,000,000         999  readTheSourceCode
      2.4        624,000,000          42  sleep
 --------   ---------------   ---------   -------------------------------------

 Kernel Statistics:

 Time (%)   Instances   Avg (ns)       Name
 --------   ---------   ------------   -------------------------------------
     61.0      inf         0.0001       make_cool_stuff<16>
     27.5      inf         0.0003       learn_something_new
     11.5      inf         0.0007       help_someone_else_ship

 Occupancy:        100%
 Warp efficiency:  100%
 Excuses issued:   0
```

<br/>

## `> stack --list --all`

### Languages
<p align="center">
  <img src="https://skillicons.dev/icons?i=cpp,c,py,rust,go,ts,js,java,bash&theme=dark" />
</p>

### AI and Machine Learning
<p align="center">
  <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn,anaconda&theme=dark" />
  <br/><br/>
  <img src="https://img.shields.io/badge/CUDA-000000?style=for-the-badge&logo=nvidia&logoColor=76B900" />
  <img src="https://img.shields.io/badge/TensorRT-000000?style=for-the-badge&logo=nvidia&logoColor=76B900" />
  <img src="https://img.shields.io/badge/cuDNN-000000?style=for-the-badge&logo=nvidia&logoColor=76B900" />
  <img src="https://img.shields.io/badge/NCCL-000000?style=for-the-badge&logo=nvidia&logoColor=76B900" />
  <img src="https://img.shields.io/badge/Triton-000000?style=for-the-badge&logo=nvidia&logoColor=76B900" />
  <img src="https://img.shields.io/badge/NeMo-000000?style=for-the-badge&logo=nvidia&logoColor=76B900" />
  <img src="https://img.shields.io/badge/CUTLASS-000000?style=for-the-badge&logo=nvidia&logoColor=76B900" />
  <img src="https://img.shields.io/badge/RAPIDS-000000?style=for-the-badge&logo=nvidia&logoColor=76B900" />
  <img src="https://img.shields.io/badge/Omniverse-000000?style=for-the-badge&logo=nvidia&logoColor=76B900" />
  <img src="https://img.shields.io/badge/Hugging%20Face-000000?style=for-the-badge&logo=huggingface&logoColor=FFD21E" />
  <img src="https://img.shields.io/badge/JAX-000000?style=for-the-badge&logo=google&logoColor=white" />
  <img src="https://img.shields.io/badge/ONNX-000000?style=for-the-badge&logo=onnx&logoColor=white" />
</p>

### Systems and Infrastructure
<p align="center">
  <img src="https://skillicons.dev/icons?i=linux,ubuntu,docker,kubernetes,aws,gcp,nginx,redis,postgres&theme=dark" />
</p>

### Graphics and Simulation
<p align="center">
  <img src="https://skillicons.dev/icons?i=blender,unreal,unity,threejs,opengl&theme=dark" />
  <br/><br/>
  <img src="https://img.shields.io/badge/Vulkan-000000?style=for-the-badge&logo=vulkan&logoColor=AC162C" />
  <img src="https://img.shields.io/badge/OptiX-000000?style=for-the-badge&logo=nvidia&logoColor=76B900" />
  <img src="https://img.shields.io/badge/PhysX-000000?style=for-the-badge&logo=nvidia&logoColor=76B900" />
</p>

### Web and Product
<p align="center">
  <img src="https://skillicons.dev/icons?i=react,nextjs,nodejs,tailwind,fastapi,graphql,vercel,figma&theme=dark" />
</p>

### Tooling
<p align="center">
  <img src="https://skillicons.dev/icons?i=git,github,githubactions,vscode,neovim,cmake,vim&theme=dark" />
  <br/><br/>
  <img src="https://img.shields.io/badge/Nsight%20Systems-000000?style=for-the-badge&logo=nvidia&logoColor=76B900" />
  <img src="https://img.shields.io/badge/Nsight%20Compute-000000?style=for-the-badge&logo=nvidia&logoColor=76B900" />
  <img src="https://img.shields.io/badge/GDB-000000?style=for-the-badge&logo=gnu&logoColor=white" />
  <img src="https://img.shields.io/badge/perf-000000?style=for-the-badge&logo=linux&logoColor=white" />
  <img src="https://img.shields.io/badge/Bazel-000000?style=for-the-badge&logo=bazel&logoColor=76B900" />
</p>

<br/>

## `> skill_matrix.csv`

```text
 DOMAIN                     LEVEL                                  STATUS
 -------------------------  -------------------------------------  ------------
 CUDA / GPU programming     [##################################--]  dangerous
 C++                        [#################################---]  fluent
 Python                     [####################################]  native
 PyTorch / deep learning    [#################################---]  fluent
 Performance engineering    [################################----]  obsessed
 Linux / systems            [################################----]  at home
 Distributed computing      [#############################-------]  scaling up
 Graphics / rendering       [###########################---------]  leveling
 Rust                       [#########################-----------]  leveling
 Full stack web             [###############################-----]  fluent
 Making it look cool        [####################################]  maxed
```

<br/>

## `> benchmarks`

<table align="center">
  <tr>
    <th>WORKLOAD</th>
    <th>BASELINE</th>
    <th>AFTERMONOS</th>
    <th>SPEEDUP</th>
  </tr>
  <tr>
    <td>idea to prototype</td>
    <td>2 weeks</td>
    <td>1 weekend</td>
    <td><b>7x</b></td>
  </tr>
  <tr>
    <td>reading a new codebase</td>
    <td>1 month</td>
    <td>3 days</td>
    <td><b>10x</b></td>
  </tr>
  <tr>
    <td>naive kernel vs tuned kernel</td>
    <td>1.00x</td>
    <td>tuned until it flies</td>
    <td><b>big</b></td>
  </tr>
  <tr>
    <td>hello world to production</td>
    <td>years</td>
    <td>2024 - 2026</td>
    <td><b>NVIDIA</b></td>
  </tr>
  <tr>
    <td>giving up on a bug</td>
    <td>eventually</td>
    <td>never</td>
    <td><b>inf</b></td>
  </tr>
</table>

<br/>

## `> system.specs`

<table align="center">
  <tr>
    <td><b>ARCHITECTURE</b></td>
    <td>Curiosity-first, build-second, ask-questions-later</td>
  </tr>
  <tr>
    <td><b>CORES</b></td>
    <td>One brain, unlimited side quests</td>
  </tr>
  <tr>
    <td><b>TENSOR CORES</b></td>
    <td>Enabled. Mixed precision thinking, full precision shipping</td>
  </tr>
  <tr>
    <td><b>CLOCK SPEED</b></td>
    <td>Boosts automatically when the idea is cool enough</td>
  </tr>
  <tr>
    <td><b>MEMORY</b></td>
    <td>Every bug ever fixed, cached forever</td>
  </tr>
  <tr>
    <td><b>BANDWIDTH</b></td>
    <td>Absorbs docs, papers and source code at line rate</td>
  </tr>
  <tr>
    <td><b>INTERCONNECT</b></td>
    <td>High bandwidth link to the people building the future</td>
  </tr>
  <tr>
    <td><b>COOLING</b></td>
    <td>San Francisco fog</td>
  </tr>
  <tr>
    <td><b>UPTIME</b></td>
    <td>2024 - 2026 @ NVIDIA, and counting</td>
  </tr>
</table>

<br/>

## `> currently --verbose`

```yaml
status:
  employer:      NVIDIA
  title:         Intern
  window:        2024 - 2026
  location:      San Francisco, CA

focus:
  - accelerated computing and everything that runs fast
  - squeezing every last FLOP out of the hardware
  - training and serving models at scale
  - turning weird ideas into working prototypes
  - learning from people way smarter than me
  - shipping things to this profile

currently_reading:
  - CUDA C++ Programming Guide (again)
  - the source code of whatever just broke
  - new papers on inference and kernel fusion

open_to:
  - collaborating on cool projects
  - talking GPUs, AI, systems, and design
  - getting nerd sniped by a good problem

philosophy: >
  make it work, make it right, make it fast.
  then make it look cool.
```

<br/>

## `> roadmap.todo`

```text
 [x]  learn to code
 [x]  fall in love with performance
 [x]  land at NVIDIA (2024)
 [x]  write a kernel that actually beats the baseline
 [x]  survive my first real profiler trace
 [ ]  ship something a million people use
 [ ]  open source more of what i build
 [ ]  write a CUDA kernel from memory without the docs
 [ ]  build something so fast it looks like a bug
 [ ]  sleep (low priority)
```

<br/>

## `> telemetry`

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=aftermonos&show_icons=true&hide_border=true&bg_color=0d1117&title_color=76B900&icon_color=76B900&text_color=c9d1d9&ring_color=76B900&include_all_commits=true&count_private=true" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=aftermonos&layout=compact&hide_border=true&bg_color=0d1117&title_color=76B900&text_color=c9d1d9&langs_count=8" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=aftermonos&hide_border=true&background=0d1117&ring=76B900&fire=76B900&currStreakLabel=76B900&sideLabels=76B900&currStreakNum=FFFFFF&sideNums=FFFFFF&dates=8b949e&stroke=21262d" />
</p>

<p align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=aftermonos&bg_color=0d1117&color=76B900&line=76B900&point=FFFFFF&area=true&area_color=76B900&hide_border=true&title_color=76B900&custom_title=aftermonos%20//%20contribution%20throughput" />
</p>

<br/>

## `> achievements --unlocked`

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=aftermonos&theme=matrix&no-frame=true&no-bg=true&margin-w=6&column=7" />
</p>

<br/>

## `> principles.md`

```text
 01  build what you think is cool. the rest follows.
 02  fast is a feature. profile before you guess.
 03  memory bandwidth is the real boss fight.
 04  ship the prototype. polish the second version.
 05  read the docs, then read the source.
 06  every bottleneck is just a puzzle with a deadline.
 07  measure twice, optimize once.
 08  the best code is the code you deleted.
 09  leave every codebase better than you found it.
 10  stay curious, stay humble, stay compiling.
```

<br/>

## `> faq`

```text
 Q: what do you do?
 A: make computers go fast and make stuff i think is cool.

 Q: what is your favorite language?
 A: whichever one the profiler likes best that day.

 Q: tabs or spaces?
 A: whatever clang-format says.

 Q: how many GPUs is enough?
 A: one more.

 Q: are you available to collab?
 A: if the idea is cool, yes. dm me on X.
```

<br/>

## `> connect`

<p align="center">
  <a href="https://x.com/aftermonous">
    <img src="https://img.shields.io/badge/X-Follow%20@aftermonous-000000?style=for-the-badge&logo=x&logoColor=white&labelColor=000000" />
  </a>
  <a href="https://github.com/aftermonos">
    <img src="https://img.shields.io/badge/GitHub-aftermonos-76B900?style=for-the-badge&logo=github&logoColor=white&labelColor=000000" />
  </a>
  <a href="https://github.com/nvidia">
    <img src="https://img.shields.io/badge/NVIDIA-GitHub-76B900?style=for-the-badge&logo=nvidia&logoColor=white&labelColor=000000" />
  </a>
</p>

<br/>

```text
aftermonos@nvidia:~$ uptime
 04:20:00 up 730 days, load average: 100.00, 100.00, 100.00

aftermonos@nvidia:~$ cat /etc/motd
 > the future runs on GPUs. i am just here making it look cool.

aftermonos@nvidia:~$ exit
[process exited with code 0]  >  see you in the next commit.
```

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:76B900,50:1a2b00,100:000000&height=140&section=footer" width="100%" />
</p>
