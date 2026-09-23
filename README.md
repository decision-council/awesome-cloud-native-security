# Awesome Cloud Native Security 🐿

![](images/banner.png)

This repository is used to collect **AWESOME** resources on the topic of cloud native security found during research.

Note:

- All resources will be suffixed and ordered by date of conferences, blogs or other formats of publication, if applicable.
- Resources in sub-list are related to their parent entries.
- For simplicity, resources would **NOT** be duplicated in two or more topics. For example, some resources about Escape of Windows Server Containers are within topic *[Windows Containers](https://github.com/brant-ruan/awesome-cloud-native-security#18-windows-containers)*.
- Contributions are welcome & appreciated :)

## 0 General

- [OWASP Cloud-Native Application Security Top 10](https://owasp.org/www-project-cloud-native-application-security-top-10/)
- [Hacking and Hardening Kubernetes Clusters by Example (KubeCon 2017)](https://github.com/sbueringer/kubecon-slides/blob/master/slides/2017-kubecon-na/Hacking%20and%20Hardening%20Kubernetes%20Clusters%20by%20Example%20%5BI%5D%20-%20Brad%20Geesaman%2C%20Symantec%20-%20Hacking%20and%20Hardening%20Kubernetes%20By%20Example%20v2.pdf)
- [2018绿盟科技容器安全技术报告 (2018-11)](https://www.nsfocus.com.cn/upload/contents/2018/11/20181109100414_79051.pdf)
    - [2020绿盟科技云原生安全技术报告 (2021-01)](http://blog.nsfocus.net/wp-content/uploads/2021/01/Technical-Report-of-Cloud-Native-Security.pdf)
- [A Measurement Study on Linux Container Security: Attacks and Countermeasures (ACSAC 2018)](https://csis.gmu.edu/ksun/publications/container-acsac18.pdf)
- [Kubernetes Security: Operating Kubernetes Clusters and Applications Safely (Book, 2018-09-28)](https://book4you.org/book/11026038/453528)
    - [Container Security: Fundamental Technology Concepts that Protect Containerized Applications (Book, 2020-04-01)](https://sg1lib.org/book/5534739/4f0c10)
- [MITRE ATT&CK framework for container runtime security with Falco. (2019-05-10)](https://sysdig.com/blog/mitre-attck-framework-for-container-runtime-security-with-sysdig-falco/)
    - [Threat matrix for Kubernetes (Microsoft, 2020-04-02)](https://www.microsoft.com/security/blog/2020/04/02/attack-matrix-kubernetes/)
        - [Microsoft's Kubernetes Threat Matrix: Here's What's Missing (2020-10-26)](https://www.darkreading.com/threat-intelligence/microsoft-s-kubernetes-threat-matrix-here-s-what-s-missing)
        - [Secure containerized environments with updated threat matrix for Kubernetes (2021-03-23)](https://www.microsoft.com/security/blog/2021/03/23/secure-containerized-environments-with-updated-threat-matrix-for-kubernetes/)
    - [国内首个云上容器ATT&CK攻防矩阵发布，阿里云助力企业容器化安全落地 (2020-06-18)](https://developer.aliyun.com/article/765449)
    - [MITRE ATT&CK Containers Matrix (2021-04-29)](https://attack.mitre.org/matrices/enterprise/containers/)
    - [最佳实践：发布国内首个K8S ATT&CK攻防矩阵 (青藤, 2021-08-25)](https://mp.weixin.qq.com/s/-FTJRl1ZK2Etgq7KO17r7w)
    - [2021西部云安全峰会召开：“云安全优才计划”发布，腾讯云安全攻防矩阵亮相 (2021-09-26)](https://mp.weixin.qq.com/s/IBTE_s-8ZO8Ac3m040-eTA)
    - [云原生安全：基于容器ATT&CK矩阵模拟攻防对抗的思考 (2021-11-01)](https://www.freebuf.com/articles/security-management/303010.html)
- [Containers' Security: Issues, Challenges, and Road Ahead (IEEE Access 2019)](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8693491)
- [企业应用容器化的攻与防 (JINQI-CON 2019)](https://github.com/neargle/slidefiles/blob/main/2019%20jingqicon%20-%20Red%20vs%20Blue%20for%20containerized%20application.pdf)
- [Sysdig 2021 Container Security and Usage Report (2021-01-01)](https://sysdig.com/wp-content/uploads/2021-container-security-and-usage-report.pdf)
- [CNCF Cloud Native Security Whitepaper (2021-02-17)](https://github.com/cncf/tag-security/blob/017e77ff380e303d80adb78e60a1f262e80df0e8/security-whitepaper/cloud-native-security-whitepaper.md)
- [Metarget：云原生攻防靶场开源啦！ (2021-05-10)](https://mp.weixin.qq.com/s?__biz=MzIyODYzNTU2OA==&mid=2247489415&idx=1&sn=4aea7b7ecff51710c79037ab07a889bc)
- [컨테이너에서 버그 찾기 어디까지 해봤니 (How to Find Container Platform Bug, CodeEngn 2021)](https://github.com/codeengn/codeengn-conference/blob/master/17/2021%20CodeEngn%20Conference%2017%2C%20컨테이너에서%20버그%20찾기%20어디까지%20해봤니%20%5B김우석%5D.pdf)
- [Kubernetes Hardening Guidance (by NSA & CISA, 2021-08-03)](https://media.defense.gov/2021/Aug/03/2002820425/-1/-1/1/CTR_KUBERNETES%20HARDENING%20GUIDANCE.PDF)
- [Kubernetes Security Checklist and Requirements](https://github.com/Vinum-Security/kubernetes-security-checklist)
- [《云原生安全：攻防实践与体系构建》](https://github.com/brant-ruan/cloud-native-security-book)
- [Security Challenges in the Container Cloud (IEEE TPS-ISA 2021)](https://github.com/brant-ruan/slides-and-papers/blob/master/TPS21.pdf)

## 1 Offensive

### 1.1 General

- [Container Security: Examining Potential Threats to the Container Environment (2019-05-14)](https://www.trendmicro.com/vinfo/us/security/news/security-technology/container-security-examining-potential-threats-to-the-container-environment)
- [云原生环境渗透工具考察 (2020-06-22)](https://wohin.me/yun-yuan-sheng-huan-jing-shen-tou-xiang-guan-gong-ju-kao-cha/)
- [红蓝对抗中的云原生漏洞挖掘及利用实录 (2021-03-02)](https://mp.weixin.qq.com/s/Aq8RrH34PTkmF8lKzdY38g)
- [靶机实验：综合场景下的渗透实战](https://github.com/brant-ruan/cloud-native-security-book/blob/main/appendix/靶机实验：综合场景下的渗透实战.pdf)
- [Exploit Symlink for Fun and Profit: from Native to Cloud Native (2021-12-08)](https://github.com/brant-ruan/slides-and-papers/blob/master/TechWorld创新沙龙-202112-symlink.pdf)

### 1.2 Kubernetes

#### 1.2.1 General

- [Walls Within Walls: What if your attacker knows parkour? (KubeCon 2019)](https://kccncna19.sched.com/event/UaeM/walls-within-walls-what-if-your-attacker-knows-parkour-tim-allclair-greg-castle-google)
    - [Walls Within Walls: What if Your Attacker Knows Parkour? (Video)](https://www.youtube.com/watch?v=6rMGRvcjvKc)
- [k0otkit：针对K8s集群的通用后渗透控制技术 (CIS 2020)](https://github.com/brant-ruan/k0otkit/blob/main/CIS2020-slide.pdf)
    - [k0otkit: Hack K8s in a K8s Way (Paper)](https://wohin.me/k0otkit-hack-k8s-in-a-k8s-way/)
    - [k0otkit: Hack K8s in a K8s Way (Video)](https://cis.freebuf.com/?id=65)
    - [Github Repo for k0otkit](https://github.com/brant-ruan/k0otkit)
- [Advanced Persistence Threats: The Future of Kubernetes Attacks (RSA 2020)](https://published-prd.lanyonevents.com/published/rsaus20/sessionsFiles/18317/2020_USA20_CSV-F01_01_Advanced%20Persistence%20Threats%20The%20Future%20of%20Kubernetes%20Attacks.pdf)
    - [Advanced Persistence Threats: The Future of Kubernetes Attacks (Video)](https://www.youtube.com/watch?v=CH7S5rE3j8w)
- [Compromising Kubernetes Cluster by Exploiting RBAC Permissions (RSA 2020)](https://published-prd.lanyonevents.com/published/rsaus20/sessionsFiles/18100/2020_USA20_DSO-W01_01_Compromising%20Kubernetes%20Cluster%20by%20Exploiting%20RBAC%20Permissions.pdf)
    - [Compromising Kubernetes Cluster by Exploiting RBAC Permissions (Video)](https://www.youtube.com/watch?v=1LMo0CftVC4)
- [Kubernetes Privilege Escalation: Excessive Permissions in Popular Platforms](https://www.paloaltonetworks.com/resources/whitepapers/kubernetes-privilege-escalation-excessive-permissions-in-popular-platforms)
    - [Kubernetes Privilege Escalation: Container Escape == Cluster Admin? (Video)](https://www.youtube.com/watch?v=oc1tq_r6VNM)
    - [Kubernetes Privilege Escalation: Container Escape == Cluster Admin? (PPT)](https://i.blackhat.com/USA-22/Thursday/US-22-Avrahami-Kubernetes-Privilege-Escalation-Container-Escape-Cluster-Admin.pdf)
- [Command and KubeCTL: Real-world Kubernetes Security for Pentesters (Shmoocon 2020)](https://docs.google.com/presentation/d/1y6KGGT5Uw27cCgFMKiGv0NjRhq8YvjY_S9UG8s_TThg/edit#slide=id.g6d20dd40e5_0_1816)
    - [Deep Dive into Real-World Kubernetes Threats (2020-02-12)](https://research.nccgroup.com/2020/02/12/command-and-kubectl-talk-follow-up/)
- [Using Kubelet Client to Attack the Kubernetes Cluster (2020-08-19)](https://www.cyberark.com/resources/threat-research-blog/using-kubelet-client-to-attack-the-kubernetes-cluster)
- [Attacking Kubernetes Clusters Through Your Network Plumbing: Part 1 (2020-11-05)](https://www.cyberark.com/resources/threat-research-blog/attacking-kubernetes-clusters-through-your-network-plumbing-part-1)
    - [Attacking Kubernetes Clusters Through Your Network Plumbing: Part 2 (2021-05-17)](https://www.cyberark.com/resources/threat-research-blog/attacking-kubernetes-clusters-through-your-network-plumbing-part-2)
- [Metadata service MITM allows root privilege escalation (EKS / GKE) (2021-02-28)](https://blog.champtar.fr/Metadata_MITM_root_EKS_GKE/)
- [etcd未授权访问的风险及修复方案详解 (2021-04-09)](https://www.anquanke.com/post/id/236831)
- [New Attacks on Kubernetes via Misconfigured Argo Workflows (2021-07-20)](https://www.intezer.com/blog/container-security/new-attacks-on-kubernetes-via-misconfigured-argo-workflows/)
- [Creating Malicious Admission Controllers (2021-08-09)](https://blog.rewanthtammana.com/creating-malicious-admission-controllers)
- [Don’t let Prometheus Steal your Fire (2021-10-12))](https://jfrog.com/blog/dont-let-prometheus-steal-your-fire/)
- [Attack Cloud Native Kubernetes (HITB 2021)](https://github.com/neargle/slidefiles/blob/main/2021%20HITB%20-%20Attack%20Cloud%20Native%20Kubernetes.pdf)
- [Metasploit in Kubernetes (2021-11-04)](https://github.com/rapid7/metasploit-framework/tree/master/kubernetes)
- [【技术推荐】云原生之Kubernetes安全 (2021-12-18)](https://mp.weixin.qq.com/s?__biz=MzI4NjE2NjgxMQ==&mid=2650258483&idx=1&sn=d05b33fa3112b1c0351dee2fca986ae8&chksm=f3e20647c4958f51a10688de8413ae142793a0f9b7ebdc07c537b5c72cf71c026e1e865de268#rd)

#### 1.2.2 Vulnerabilities and Exploits

- [Understanding about CVE-2017–1002101 on kubernetes (2018-03-19)](https://makocchi.medium.com/kubernetes-cve-2017-1002101-en-5a30bf701a3e)
    - [Fixing the Subpath Volume Vulnerability in Kubernetes (2018-04-04)](https://kubernetes.io/blog/2018/04/04/fixing-subpath-volume-vulnerability/)
    - [ExP: CVE-2017-1002101 by bgeesaman](https://github.com/bgeesaman/subpath-exploit)
    - [CVE-2017-1002101：突破隔离访问宿主机文件系统](https://github.com/brant-ruan/cloud-native-security-book/blob/main/appendix/CVE-2017-1002101：突破隔离访问宿主机文件系统.pdf)
    - [逃逸风云再起：从CVE-2017-1002101到CVE-2021-25741 (2021-10-12)](https://mp.weixin.qq.com/s/RqaWvzXZR6sLPzBI8ljoxg)
- [Exploiting path traversal in kubectl cp (CVE-2018-1002100, 2018-05-04)](https://hansmi.ch/articles/2018-04-openshift-s2i-security#poc-kubectl-cp)
    - [Disclosing a directory traversal vulnerability in Kubernetes copy – CVE-2019-1002101 (2019-03-28)](https://unit42.paloaltonetworks.com/disclosing-directory-traversal-vulnerability-kubernetes-copy-cve-2019-1002101/)
    - [CVE-2019-11246: Clean links handling in cp's tar code (2019-04-30)](https://github.com/kubernetes/kubernetes/pull/76788)
    - [CVE-2019-11249: Incomplete fixes for CVE-2019-1002101 and CVE-2019-11246, kubectl cp potential directory traversal (2019-08-05)](https://github.com/kubernetes/kubernetes/issues/80984)
    - [CVE-2019-11251: kubectl cp symlink vulnerability (2020-02-03)](https://github.com/kubernetes/kubernetes/issues/87773)
- [The Story of the First Kubernetes Critical CVE (CVE-2018-1002105, 2018-12-04)](https://rancher.com/blog/2018/2018-12-04-k8s-cve/)
    - [CVE-2018-1002105（k8s特权提升）原理与利用分析报告 (2018-12-08)](https://xz.aliyun.com/t/3542)
- [CVE-2018-1002103：远程代码执行与虚拟机逃逸](https://github.com/brant-ruan/cloud-native-security-book/blob/main/appendix/CVE-2018-1002103：远程代码执行与虚拟机逃逸.pdf)
- [Kubernetes hostPort allow services traffic interception when using kubeproxy IPVS  (CVE-2019-9946, 2019-03-28)](http://blog.champtar.fr/CVE-2019-9946/)
- [Non-Root Containers, Kubernetes CVE-2019-11245 and Why You Should Care, (2019-08-28)](https://unit42.paloaltonetworks.com/non-root-containers-kubernetes-cve-2019-11245-care/)
- [When it’s not only about a Kubernetes CVE... (CVE-2020-8555, 2020-06-03)](https://medium.com/@BreizhZeroDayHunters/when-its-not-only-about-a-kubernetes-cve-8f6b448eafa8)
- [Kubernetes Vulnerability Puts Clusters at Risk of Takeover (CVE-2020-8558, 2020-07-27)](https://unit42.paloaltonetworks.com/cve-2020-8558/)
- [Kubernetes man in the middle using LoadBalancer or ExternalIPs (CVE-2020-8554, 2020-12-08)](https://blog.champtar.fr/K8S_MITM_LoadBalancer_ExternalIPs/)
    - [Protecting Against an Unfixed Kubernetes Man-in-the-Middle Vulnerability (CVE-2020-8554, 2020-12-21)](https://unit42.paloaltonetworks.com/cve-2020-8554/)
- [Host MITM attack via IPv6 rogue router advertisements (K8S CVE-2020-10749 / Docker CVE-2020-13401 / LXD / WSL2 / …) (2021-02-28)](https://blog.champtar.fr/IPv6_RA_MITM/)
- [Exploiting and detecting CVE-2021-25735: Kubernetes validating admission webhook bypass (2021-04-28)](https://sysdig.com/blog/cve-2021-25735-kubernetes-admission-bypass/)
    - [ExP: CVE-2021-25735 by darryk10](https://github.com/darryk10/CVE-2021-25735)
- [Detecting and Mitigating CVE-2021-25737: EndpointSlice validation enables host network hijack (2021-05-24)](https://sysdig.com/blog/cve-2021-25737-endpointslice/)
- [浅谈云上攻防——CVE-2020-8562漏洞为k8s带来的安全挑战 (2021-10-25)](https://mp.weixin.qq.com/s/HCBL7SND_-IZqeqX_vchug)
- [cr8escape: New Vulnerability in CRI-O Container Engine Discovered by CrowdStrike (CVE-2022-0811)](https://www.crowdstrike.com/blog/cr8escape-new-vulnerability-discovered-in-cri-o-container-engine-cve-2022-0811/)
    - [谁动了我的core\_pattern？CVE-2022-0811容器逃逸漏洞分析](https://cloud.tencent.com/developer/article/1981066)

### 1.3 Container

#### 1.3.1 General

- [Abusing Privileged and Unprivileged Linux Containers (2016-06-01)](https://www.nccgroup.com/globalassets/our-research/us/whitepapers/2016/june/container_whitepaper.pdf)
- [Bypassing Docker Authz Plugin and Using Docker-Containerd for Privesc (2019-07-11)](https://staaldraad.github.io/post/2019-07-11-bypass-docker-plugin-with-containerd/)
- [A Methodology for Penetration Testing Docker Systems (Bachelor Theses, 2020-01-17)](https://www.cs.ru.nl/bachelors-theses/2020/Joren_Vrancken___4593847___A_Methodology_for_Penetration_Testing_Docker_Systems.pdf)
    - [针对容器的渗透测试方法 (2020-04-17)](https://mp.weixin.qq.com/s?subscene=19&__biz=MzIyODYzNTU2OA==&mid=2247487590&idx=1&sn=060a8bdf2ddfaff6ceae5cb931cb27ab&chksm=e84fb6b9df383faf1723040a0d6f0300c9517db902ef0010e230d8e802b1dfe9d8b95e6aabbd)
- [里应外合：借容器root提权 (2020-12-03)](https://wohin.me/li-ying-wai-he-jie-zhu-rong-qi-root/)
- [CVE-2021-21287: 容器与云的碰撞——一次对MinIO的测试 (2021-01-30)](https://www.leavesongs.com/PENETRATION/the-collision-of-containers-and-the-cloud-pentesting-a-MinIO.html)
- [New Vulnerability Affecting Container Engines CRI-O and Podman (CVE-2021-20291) (2021-04-14)](https://unit42.paloaltonetworks.com/cve-2021-20291/)

#### 1.3.2 Container Escape

- [Container escape through open_by_handle_at (shocker exploit) (2014-06-18)](https://lists.linuxcontainers.org/pipermail/lxc-users/2014-June/007248.html)
    - [Docker breakout exploit analysis (2014-06-19)](https://medium.com/@fun_cuddles/docker-breakout-exploit-analysis-a274fff0e6b3)
    - [PoC: Shocker by gabrtv](https://github.com/gabrtv/shocker)
    - [Docker 容器逃逸案例分析 (2016-07-19)](https://developer.aliyun.com/article/57803)
- [Dirty COW - (CVE-2016-5195) - Docker Container Escape (2017-09)](https://blog.paranoidsoftware.com/dirty-cow-cve-2016-5195-docker-container-escape/)
    - [ExP: CVE-2016-5195 by scumjr](https://github.com/scumjr/dirtycow-vdso)
- [Escaping Docker container using waitid() – CVE-2017-5123 (2017-12-27)](https://web.archive.org/web/20180626023815/https://www.twistlock.com/2017/12/27/escaping-docker-container-using-waitid-cve-2017-5123/)
    - [Escaping Docker container using waitid() - CVE-2017-5123 (Video)](https://www.youtube.com/watch?v=IdRDFS4u2rQ)
- [A Compendium of Container Escapes (Black Hat 2019)](https://capsule8.com/assets/ug/us-19-Edwards-Compendium-Of-Container-Escapes.pdf)
- [In-and-out - Security of Copying to and from Live Containers (Open Source Summit 2019)](https://osseu19.sched.com/event/TLC4/in-and-out-security-of-copying-to-and-from-live-containers-ariel-zelivansky-yuval-avrahami-twistlock)
- [CVE-2019-5736: Escape from Docker and Kubernetes containers to root on host (2019-02-13)](https://blog.dragonsector.pl/2019/02/cve-2019-5736-escape-from-docker-and.html)
    - [ExP: CVE-2019-5736 by Frichetten](https://github.com/Frichetten/CVE-2019-5736-PoC)
    - [Escaping a Broken Container - 'namespaces' from 35C3 CTF (2019-04-15)](http://blog.perfect.blue/namespaces-35c3ctf)
    - [容器逃逸成真：从CTF到CVE-2019-5736 (2019-11-20)](https://wohin.me/rong-qi-tao-yi-cheng-zhen-cong-ctfjie-ti-dao-cve-2019-5736lou-dong-wa-jue-fen-xi/)
- [An Exercise in Practical Container Escapology (2019-03-07)](https://capsule8.com/blog/practical-container-escape-exercise/)
- [Felix Wilhelm's Twitter on the Escape Technique utilizing release_agent (2019-07-17)](https://twitter.com/_fel1x/status/1151487051986087936?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E1151487053370187776%7Ctwgr%5E%7Ctwcon%5Es2_&ref_url=https%3A%2F%2Fajxchapman.github.io%2Fcontainers%2F2020%2F11%2F19%2Fprivileged-container-escape.html)
    - [Understanding Docker container escapes (2019-07-19)](https://blog.trailofbits.com/2019/07/19/understanding-docker-container-escapes/)
    - [Privileged Container Escape - Control Groups release_agent (2020-11-19)](https://ajxchapman.github.io/containers/2020/11/19/privileged-container-escape.html)
- [Kubernetes Pod Escape Using Log Mounts (2019-08-01)](https://blog.aquasec.com/kubernetes-security-pod-escape-log-mounts)
    - [Kubelet follows symlinks as root in /var/log from the /logs server endpoint (debate on hackerone, 2021-04-02)](https://hackerone.com/reports/1036886)
    - [PoC: kube-pod-escape](https://github.com/danielsagi/kube-pod-escape)
- [Original Tweet on CVE-2019-16884 (2019-09-22)](https://twitter.com/adam_iwaniuk/status/1175741830136291328)
- [CVE-2019-19921: Volume mount race condition with shared mounts (2020-01-01)](https://github.com/opencontainers/runc/issues/2197)
    - [PoC: runc-masked-race.sh](https://gist.github.com/leoluk/82965ad9df58247202aa0e1878439092)
    - [PATCH RFC 1/1 mount: universally disallow mounting over symlinks (2019-12-30)](https://lore.kernel.org/stable/20191230052036.8765-2-cyphar@cyphar.com/)
- [容器逃逸技术概览 (2020-02-21)](https://wohin.me/rong-qi-tao-yi-gong-fang-xi-lie-yi-tao-yi-ji-zhu-gai-lan/)
- [Escaping Virtualized Containers (Black Hat 2020)](https://i.blackhat.com/USA-20/Thursday/us-20-Avrahami-Escaping-Virtualized-Containers.pdf)
    - [Kata Containers逃逸研究 (2020-09-25)](https://mp.weixin.qq.com/s/q4xJtlO6iFpHQginGvVBDQ)
    - [Security advisory for four vulnerabilities in Kata Containers (2020-12-04)](https://bugs.launchpad.net/katacontainers.io/+bug/1863875)
- [CVE-2020-14386: Privilege Escalation Vulnerability in the Linux kernel (2020-10-09)](https://unit42.paloaltonetworks.com/cve-2020-14386/)
    - [Containing a Real Vulnerability (2020-09-18)](https://gvisor.dev/blog/2020/09/18/containing-a-real-vulnerability/)
- [host模式容器逃逸漏洞（CVE-2020-15257）技术分析 (2020-12-02)](https://mp.weixin.qq.com/s/WmSaLPnG4o4Co1xRiYCOnQ)
    - [ABSTRACT SHIMMER (CVE-2020-15257): Host Networking is root-Equivalent, Again (2020-12-10)](https://research.nccgroup.com/2020/12/10/abstract-shimmer-cve-2020-15257-host-networking-is-root-equivalent-again/)
    - [容器逃逸CVE-2020-15257 containerd-shim Exploit开发 (2020-12-14)](https://www.cdxy.me/?p=837)
- [The Strange Case of How We Escaped the Docker Default Container (CVE-2020-27352, 2021-03-04)](https://www.cyberark.com/resources/threat-research-blog/the-strange-case-of-how-we-escaped-the-docker-default-container)
- [runc mount destinations can be swapped via symlink-exchange to cause mounts outside the rootfs (CVE-2021-30465, 2021-05-30)](http://blog.champtar.fr/runc-symlink-CVE-2021-30465/)
    - [RunC TOCTOU逃逸CVE-2021-30465分析 (2021-08-18)](https://zhuanlan.zhihu.com/p/401057262)
- [利用Linux内核漏洞实现Docker逃逸 (2021-06-11)](https://mp.weixin.qq.com/s/ea8YLaXjSjKcN4MNgMi2aQ)
- [【安全干货】Docker CVE-2018-6552 (2021-06-30)](https://mp.weixin.qq.com/s?__biz=Mzg5NjEyMjA5OQ==&mid=2247486707&idx=1&sn=0cd7dea2347f19beb703088947932b4f)
- [CVE-2021-22555: Turning \x00\x00 into 10000$ (2021-07-07)](https://google.github.io/security-research/pocs/linux/cve-2021-22555/writeup.html)
    - [CVE-2021-22555：Linux 内核提权导致 Docker 逃逸 (2021-07-23)](https://mp.weixin.qq.com/s?__biz=MzI1NDQxMDE0NQ==&mid=2247484015&idx=1&sn=74755a7113cd13655239d885c34562f0)
- [With Friends like eBPF, who needs enemies? (Defcon 29)](https://i.blackhat.com/USA21/Wednesday-Handouts/us-21-With-Friends-Like-EBPF-Who-Needs-Enemies.pdf)
- [Container Escape in 2021 (HITB 2021)](https://conference.hitb.org/hitbsecconf2021sin/materials/D2T2%20-%20Ccntainer%20Escape%20in%202021%20-%20Li%20Qiang.pdf)
    - [Container Escape in 2021 (KCon 2021)](https://github.com/knownsec/KCon/blob/master/2021/Container%20escape%20in%202021.pdf)
- [Finding Azurescape – Cross-Account Container Takeover in Azure Container Instances (2021-09-09)](https://unit42.paloaltonetworks.com/azure-container-instances/)
- [云原生安全攻防｜使用eBPF逃逸容器技术分析与实践 (2021-11-03)](https://mp.weixin.qq.com/s/Psqy3X3VdUPga7f2cnct1g)
- [Overflow in netlink bytemsg length field allows attacker to override netlink-based container configuration (CVE-2021-43784, 2021-12-06)](https://github.com/opencontainers/runc/security/advisories/GHSA-v95c-p5hm-xq8f)
    - [Issue 2241: runc/libcontainer: insecure handling of bind mount sources](https://bugs.chromium.org/p/project-zero/issues/detail?id=2241)
- [Podman Time-of-check Time-of-use (TOCTOU) Race Condition (CVE-2023-0778)](https://github.com/advisories/GHSA-qwqv-rqgf-8qh8)
- [Attacks are Forwarded: Breaking the Isolation of MicroVM-based Containers Through Operation Forwarding](https://www.usenix.org/system/files/usenixsecurity23-xiao-jietao.pdf)

#### 1.3.3 Container DoS

- [Houdini’s Escape: Breaking the Resource Rein of Linux Control Groups (CCS 2019)](http://www.cs.memphis.edu/~xgao1/paper/ccs19.pdf)
    - [Houdini’s Escape: Breaking the Resource Rein of Linux Control Groups (Video)](https://www.youtube.com/watch?v=PPo9sQnJaec)
- [Docker组件间标准输入输出复制的DoS攻击分析 (网络信息安全学报 2020)](http://www.infocomm-journal.com/cjnis/CN/10.11959/j.issn.2096-109x.2020074)
- [Demons in the Shared Kernel: Abstract Resource Attacks Against OS-level Virtualization (CCS 2021)](https://wenboshen.org/assets/papers/LogicalDoS.pdf)

### 1.4 Serverless

- [Hacking Serverless Runtimes (Black Hat 2017)](https://www.blackhat.com/docs/us-17/wednesday/us-17-Krug-Hacking-Severless-Runtimes.pdf)
    - [Hacking Serverless Runtimes (Whitepaper)](https://www.blackhat.com/docs/us-17/wednesday/us-17-Krug-Hacking-Severless-Runtimes-wp.pdf)
- [Serverless Toolkit for Pentesters (2018-11-11)](https://blog.ropnop.com/serverless-toolkit-for-pentesters/)
- [Serverless Red Team Infrastructure: Part 1, Web Bugs (2018-09)](https://www.mdsec.co.uk/2018/09/serverless-red-team-infrastructure-part-1-web-bugs/)
- [针对AWS Lambda的运行时攻击 (2020-12-02)](https://mp.weixin.qq.com/s?__biz=MzIyODYzNTU2OA==&mid=2247488901&idx=1&sn=4d7bdb1ddf015cb77ea4e8bc0978712f&chksm=e84fb35adf383a4ca9e9b7cb0dce91cf757e043d74201361537aa6cd0e80cf6afaf1c63eb1e5&mpshare=1&scene=1&srcid=0331LaY4vmtzqLyDuZ41Y8GB&sharer_sharetime=1617201942068&sharer_shareid=353a216cfe47b39b5c642fc1dbddb3ef&version=3.1.0.2353&platform=mac#rd)
- [How We Escaped Docker in Azure Functions (2021-01-27)](https://www.intezer.com/blog/research/how-we-escaped-docker-in-azure-functions/)
    - [Royal Flush: Privilege Escalation Vulnerability in Azure Functions (2021-04-08)](https://www.intezer.com/blog/cloud-security/royal-flush-privilege-escalation-vulnerability-in-azure-functions/)
- [RT又玩新套路，竟然这样隐藏C2 (2021-04-21)](https://mp.weixin.qq.com/s/ouvfGPnkFs2C_FCKO5Q_sQ)
- [CDN+FaaS打造攻击前置 (2021-08-11)](https://mp.weixin.qq.com/s/6SAgy16Uja42GksLJdRHOg)

### 1.6 Service Mesh

- [A Survey of Istio’s Network Security Features (2020-03-04)](https://research.nccgroup.com/2020/03/04/a-survey-of-istios-network-security-features/)
- [Istio访问授权再曝高危漏洞 (CVE-2020-8595, 2020-03-13)](https://mp.weixin.qq.com/s/IHJAsO2SktNXqQGNLuTYUQ)
- [Attack in a Service Mesh (CIS 2020)](https://github.com/neargle/slidefiles/blob/main/2020%20CIS%20-%20Attack%20in%20a%20Service%20Mesh%20-%20Public.pptx.pdf)
- [Istio Security Assessment (2021-07-13 (disclosed), 2020-08-06 (accomplished) by Istio with NCC Group)](https://istio.io/latest/blog/2021/ncc-security-assessment/NCC_Group_Google_GOIST2005_Report_2020-08-06_v1.1.pdf)

### 1.7 API Gateway

- [腾讯蓝军安全提醒：开源云原生API网关Kong可能会成为攻击方进入企业内网的新入口(CVE-2020-11710) (2020-04-15)](https://security.tencent.com/index.php/announcement/msg/193)

### 1.8 Windows Containers

- [Well, That Escalated Quickly! How Abusing Docker API Led to Remote Code Execution, Same Origin Bypass and Persistence in The Hypervisor via Shadow Containers (Black Hat 2017)](https://www.blackhat.com/docs/us-17/thursday/us-17-Cherny-Well-That-Escalated-Quickly-How-Abusing-The-Docker-API-Led-To-Remote-Code-Execution-Same-Origin-Bypass-And-Persistence.pdf)
    - [Well, That Escalated Quickly! (Whitepaper)](https://www.blackhat.com/docs/us-17/thursday/us-17-Cherny-Well-That-Escalated-Quickly-How-Abusing-The-Docker-API-Led-To-Remote-Code-Execution-Same-Origin-Bypass-And-Persistence_wp.pdf)
- [What I Learned from Reverse Engineering Windows Containers (2019-12-12)](https://unit42.paloaltonetworks.com/what-i-learned-from-reverse-engineering-windows-containers/)
- [Windows Server Containers Are Open, and Here's How You Can Break Out (2020-07-15)](https://unit42.paloaltonetworks.com/windows-server-containers-vulnerabilities/)
    - [PoC by James Forshaw (the author of post *Who Contains the Containers?*)](https://gist.github.com/tyranid/bf8a890e615d310c7193901a1c7e0e3a)
- [Who Contains the Containers? (Project Zero, 2021-04-01)](https://googleprojectzero.blogspot.com/2021/04/who-contains-containers.html)

### 1.9 Tools

- [kube-hunter - Hunt for security weaknesses in Kubernetes clusters](https://github.com/aquasecurity/kube-hunter)
- [serverless_toolkit - A collection of useful Serverless functions I use when pentesting](https://github.com/ropnop/serverless_toolkit)
- [kubesploit](https://github.com/cyberark/kubesploit)
- [kubeletmein - Security testing tool for Kubernetes, abusing kubelet credentials on public cloud providers](https://github.com/4ARMED/kubeletmein)
- [CDK - Zero Dependency Container Penetration Toolkit](https://github.com/cdk-team/CDK)
    - [Zero Dependency Container Penetration Toolkit (Blackhat 2021)](https://github.com/neargle/slidefiles/blob/main/2021%20BlackHat%20ASIA%20Arsenal%20-%20Zero%20Dependency%20Container%20Penetration%20Toolkit.pdf)
    - [CDK: Also a Awesome BugBounty Tool for Cloud Platform (WHC 2021)](https://github.com/neargle/slidefiles/blob/main/2021%20WHC2021%20CDK-Also-a-Awesome-BugBounty-Tool-for-Cloud-Platform.pptx.pdf)
- [Metarget - framework providing automatic constructions of vulnerable infrastructures](https://github.com/brant-ruan/metarget)
- [red-kube - Red Team K8S Adversary Emulation Based on kubectl](https://github.com/lightspin-tech/red-kube)
- [whoc - A container image that extracts the underlying container runtime](https://github.com/twistlock/whoc)
- [kdigger - A context discovery tool for Kubernetes penetration testing](https://github.com/quarkslab/kdigger)
    - [Introduction to kdigger](https://blog.quarkslab.com/kdigger-a-context-discovery-tool-for-kubernetes.html)
- [RowShield](https://rowshield.dev) - Probes a deployed Supabase app for reachable and exposed data, then monitors connected projects for RLS and schema drift.

## 2 Defensive

### 2.1 Standards and Benchmarks

- [NIST.SP.800-190 Application Container Security Guide (2017-09-25)](https://csrc.nist.gov/publications/detail/sp/800-190/final)
- [NIST.IR.8176 Security Assurance Requirements for Linux Application Container Deployments (2017-10)](https://nvlpubs.nist.gov/nistpubs/ir/2017/NIST.IR.8176.pdf)
- [OWASP Container Security Verification Standard](https://github.com/OWASP/Container-Security-Verification-Standard)
- [CIS Kubernetes Benchmark](https://www.cisecurity.org/benchmark/kubernetes/)
- [CIS Docker Benchmark](https://www.cisecurity.org/benchmark/docker/)
- [NIST.SP.800-204 Security Strategies for Microservices-based Application Systems (2019-08)](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-204.pdf)
    - [NIST.SP.800-204B Attribute-based Access Control for Microservices-based Applications Using a Service Mesh (2021-08)](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-204B.pdf)

### 2.2 Kubernetes

- [Kubernetes中的异常活动检测 (KCon 2021)](https://github.com/knownsec/KCon/blob/master/2021/kubernetes中的异常活动检测.pdf)

### 2.3 Container

- [Understanding and Hardening Linux Containers (2016-06-29)](https://research.nccgroup.com/wp-content/uploads/2020/07/ncc_group_understanding_hardening_linux_containers-1-1.pdf)
- [探索Sysdig Falco：容器环境下的异常行为检测工具 (2019-09-25)](https://wohin.me/tan-suo-sysdig-falco-rong-qi-huan-jing-xia-de-yi-chang-xing-wei-jian-ce-gong-ju/)
- [云原生之容器安全实践 (2020-03-12)](https://tech.meituan.com/2020/03/12/cloud-native-security.html)
- [容器环境相关的内核漏洞缓解技术 (2020-08-31)](https://mp.weixin.qq.com/s?__biz=MzIyODYzNTU2OA==&mid=2247488536&idx=1&sn=fd2fcb732e76b2243f972f7a79be2b19)
- [Detecting a Container Escape with Cilium and eBPF](https://isovalent.com/blog/post/2021-11-container-escape)

### 2.4 Secure Container

- [Making Containers More Isolated: An Overview of Sandboxed Container Technologies (2019-06-06)](https://unit42.paloaltonetworks.com/making-containers-more-isolated-an-overview-of-sandboxed-container-technologies/)
- [深度解析 AWS Firecracker 原理篇 – 虚拟化与容器运行时技术 (2019-12-09)](https://aws.amazon.com/cn/blogs/china/deep-analysis-aws-firecracker-principle-virtualization-container-runtime-technology/)
- [以Docker为代表的传统容器到了生死存亡之际 (2019-12-24)](https://mp.weixin.qq.com/s/3OkDCNdwumIP9qj_FS_Kzg)
- [Kata Containers创始人：安全容器导论 (2019-12-26)](https://mp.weixin.qq.com/s?__biz=MzI0Nzc3MTQyMw==&mid=2247490237&idx=1&sn=eebe19ed1f693400cbad9b6e91b5dfb4&chksm=e9aba2cddedc2bdbae69c61f49b014f95052f377daa65f7522dbae92fe5fde62edecd70a7eca&token=347966226&lang=zh_CN#rd)

### 2.5 Network

- [BASTION: A Security Enforcement Network Stack for Container Networks (USENIX 2020)](https://www.usenix.org/system/files/atc20-nam.pdf)

### 2.6 Practices

- [国外顶尖容器安全产品是怎么做的 (2020-12-04)](https://mp.weixin.qq.com/s/JypEOt3N0li9l1KToToHZA)
- [云原生｜容器和应用安全运营实践思考 (2021-09-07)](https://mp.weixin.qq.com/s/rRJLW5ZaecEjnLIWjQqs9g)

### 2.7 Tools

- [docker-bench-security](https://github.com/docker/docker-bench-security)
- [kube-bench](https://github.com/aquasecurity/kube-bench)
- [KubiScan](https://github.com/cyberark/KubiScan)
- [Falco](https://github.com/falcosecurity/falco)
    - [Bypass Falco (2020-11-20)](https://static.sched.com/hosted_files/kccncna20/56/Bypass%20Falco%20%5BKubeCon%20%2B%20CloudNativeCon%20NA%202020%5D.pdf)
    - [Detecting MITRE ATT&CK: Defense evasion techniques with Falco (2021-02-02)](https://sysdig.com/blog/mitre-defense-evasion-falco/)
    - [Detecting MITRE ATT&CK: Privilege escalation with Falco (2021-03-02)](https://sysdig.com/blog/mitre-privilege-escalation-falco/)
- [Elkeid - Elkeid is a Cloud-Native Host-Based Intrusion Detection solution project to provide next-generation Threat Detection and Behavior Audition with modern architecture](https://github.com/bytedance/Elkeid)
- [kubescape - kubescape is the first tool for testing if Kubernetes is deployed securely as defined in Kubernetes Hardening Guidance by to NSA and CISA](https://github.com/armosec/kubescape)
- [veinmind-tools](https://github.com/chaitin/veinmind-tools)
- [cnspec - cloud-native security and policy project](https://cnspec.io)

## 3 Incidents

- [Lessons from the Cryptojacking Attack at Tesla (2018-02-20)](https://web.archive.org/web/20180222103919/https://blog.redlock.io/cryptojacking-tesla)
- [Graboid: First-Ever Cryptojacking Worm Found in Images on Docker Hub (2019-10-15)](https://unit42.paloaltonetworks.com/graboid-first-ever-cryptojacking-worm-found-in-images-on-docker-hub/)
- [Detect large-scale cryptocurrency mining attack against Kubernetes clusters (2020-04-08)](https://azure.microsoft.com/en-us/blog/detect-largescale-cryptocurrency-mining-attack-against-kubernetes-clusters/)
- [Coinminer, DDoS Bot Attack Docker Daemon Ports (2020-05-06)](https://www.trendmicro.com/vinfo/us/security/news/virtualization-and-cloud/coinminer-ddos-bot-attack-docker-daemon-ports)
    - [TeamTNT团伙对Docker主机发起攻击活动，植入挖矿木马 (2020-08-04)](https://mp.weixin.qq.com/s?__biz=MzI5NjA0NjI5MQ==&mid=2650166823&idx=1&sn=4bb43461b3159a2ef8ff21d244dc10ed)
    - [Team TNT – The First Crypto-Mining Worm to Steal AWS Credentials (2020-08-16)](https://www.cadosecurity.com/team-tnt-the-first-crypto-mining-worm-to-steal-aws-credentials/)
    - [Cetus: Cryptojacking Worm Targeting Docker Daemons (2020-08-27)](https://unit42.paloaltonetworks.com/cetus-cryptojacking-worm/)
    - [Black-T: New Cryptojacking Variant from TeamTNT (2020-10-05)](https://unit42.paloaltonetworks.com/black-t-cryptojacking-variant/)
    - [TeamTNT 挖矿木马利用Docker Remote API未授权访问漏洞入侵云服务器 (2020-11-27)](https://s.tencent.com/research/report/1185.html)
    - [TeamTNT Now Deploying DDoS-Capable IRC Bot TNTbotinger (2020-12-18)](https://www.trendmicro.com/en_us/research/20/l/teamtnt-now-deploying-ddos-capable-irc-bot-tntbotinger.html)
    - [Hildegard: New TeamTNT Cryptojacking Malware Targeting Kubernetes (2021-02-03)](https://unit42.paloaltonetworks.com/hildegard-malware-teamtnt/)
    - [TeamTNT Targets Kubernetes, Nearly 50,000 IPs Compromised in Worm-like Attack (2021-05-25)](https://www.trendmicro.com/en_nl/research/21/e/teamtnt-targets-kubernetes--nearly-50-000-ips-compromised.html)
    - [Tracking the Activities of TeamTNT: A Closer Look at a Cloud-Focused Malicious Actor Group (2021-06)](https://documents.trendmicro.com/assets/white_papers/wp-tracking-the-activities-of-teamTNT.pdf)
    - [TeamTNT Actively Enumerating Cloud Environments to Infiltrate Organizations (2021-06-04)](https://unit42.paloaltonetworks.com/teamtnt-operations-cloud-environments/)
    - [TeamTNT with new campaign aka "Chimaera" (2021-09-08)](https://cybersecurity.att.com/blogs/labs-research/teamtnt-with-new-campaign-aka-chimaera)
    - [Team TNT Deploys Malicious Docker Image On Docker Hub (2021-10-07)](https://www.uptycs.com/blog/team-tnt-deploys-malicious-docker-image-on-docker-hub-with-pentesting-tools)
    - [再次捕获云上在野容器攻击，TeamTNT黑产攻击方法揭秘 (2021-10-20)](https://mp.weixin.qq.com/s/9ZSxpeUHTcgQrQ1Ys5uROw)
    - [Compromised Docker Hub Accounts Abused for Cryptomining Linked to TeamTNT (2021-11-09)](https://www.trendmicro.com/en_us/research/21/k/compromised-docker-hub-accounts-abused-for-cryptomining-linked-t.html)
- [Misconfigured Kubeflow workloads are a security risk (2020-06-10)](https://www.microsoft.com/security/blog/2020/06/10/misconfigured-kubeflow-workloads-are-a-security-risk/)
- [鉴权配置不当，蠕虫在自建K8s集群自由出入 (2020-09-16)](https://developer.aliyun.com/article/772455)
- [Siloscape: First Known Malware Targeting Windows Containers to Compromise Cloud Environments (2021-06-07)](https://unit42.paloaltonetworks.com/siloscape/)
- [NSA, Partners Release Cybersecurity Advisory on Brute Force Global Cyber Campaign (2021-07-01)](https://www.nsa.gov/news-features/press-room/Article/2677750/nsa-partners-release-cybersecurity-advisory-on-brute-force-global-cyber-campaign/)
    - [Russian GRU Conducting Global Brute Force Campaign to Compromise Enterprise and Cloud Environments (2021-07)](https://media.defense.gov/2021/Jul/01/2002753896/-1/-1/1/CSA_GRU_GLOBAL_BRUTE_FORCE_CAMPAIGN_UOO158036-21.PDF)
- [DockerHub再现百万下载量黑产镜像，小心你的容器被挖矿 (2021-08-30)](https://mp.weixin.qq.com/s?__biz=MzU3ODAyMjg4OQ==&mid=2247490656&idx=1&sn=8d86694b96f7c78aaba149bc123b620f)
- [Misconfigured Kafdrop Puts Companies’ Apache Kafka Completely Exposed (2021-12-06)](https://spectralops.io/blog/misconfigured-kafdrop-puts-companies-apache-kafka-completely-exposed/)
