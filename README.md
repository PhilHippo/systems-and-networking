# Systems and Networking - Unit I (2021-2022)

[News](#News) | [General Information](#General-Information) | [Syllabus](#Syllabus) | [Class Schedules](#Class-Schedules) |

## News
- All the students that are willing to attend this class (either in-person or remotely) **must subscribe ASAP** to the Moodle web page of the course, as indicated [below](#Moodle-Web-Page).
- Classes will start on **Wednesday, September 29 at 11:00AM**. Students are kindly asked to refer to the class schedule at the following [link](https://acsai.di.uniroma1.it/#schedule). For any further information on how to attend classes, please keep an eye on the dedicated [web page](https://www.uniroma1.it/en/notizia/covid-19-phase-3-person-and-online-classes-exams-and-graduation-sessions)

## General Information

Welcome to the System and Networking - Unit I class!

This is a second-year, first-semester course of the [BSc in Applied Computer Science and Artificial Intelligence of Sapienza University of Rome](https://acsai.di.uniroma1.it/).

This repository contains class material along with any useful information for the 2021-2022 academic year.

### Class Schedule
- **Wednesday** from **11:00AM** to **1:00PM**
- **Thursday** from **8:00AM** to **11:00AM**

### How to Attend Classes
According to the guidelines provided by Sapienza University to contrast the COVID-19 pandemic, the course will be held **both** in-person and remotely. For any further information, students must refer to the official documentation available on the [Sapienza website](https://www.uniroma1.it/en/notizia/covid-19-phase-3-person-and-online-classes-exams-and-graduation-sessions).

#### Attending Classes in Person: Room 2L - Via del Castro Laurenziano 7a	
Students who are willing to attend classes in presence must issue their request through the [Prodigit Sapienza](https://prodigit.uniroma1.it/) online booking system, according to the rules established (please, see [here](https://www.uniroma1.it/en/notizia/covid-19-phase-3-person-and-online-classes-exams-and-graduation-sessions)).

#### Attending Classes Remotely: Zoom
Students who are willing to attend classes remotely online will need to register to the dedicated Zoom conference, using the following link: **TBA**

### Moodle Web Page
Students must subscribe to the Moodle web page using the same credentials (username/password) to access Wi-Fi network and Infostud services, at the following link: https://elearning.uniroma1.it/course/view.php?id=13817

### Office Hours
- Please, drop me a message to <a href="mailto:tolomei@di.uniroma1.it">tolomei@di.uniroma1.it</a> if you like to arrange an in-person meeting or schedule a remote call either on Google Meet or Zoom.<br/>
In-person meetings will be held in my office, which is located in Room 106 at the 1st floor of Building E in viale Regina Elena 295.

### Contacts
- Email: tolomei@di.uniroma1.it
- Website: https://www.di.uniroma1.it/~tolomei
- Bacheca Sapienza: https://corsidilaurea.uniroma1.it/it/users/gabrieletolomeiuniroma1it

### Description and Goals
The _Operating System_ (OS) is the key component of any modern computing device. Moreover, it very well represents a fundamental concept at the heart of any Computer Science curriculum, namely _abstraction_.

More specifically, by virtualizing the physical resources of a computer system, OS allows programmers to develop software applications without worrying about the nitty-gritty of the hardware. Decoupling the software from the hardware guarantees more flexibility for the system developer as well as greater usability for the end user.
It is therefore essential for any Computer Science student to have the ability to comprehend how to effectively and efficiently design and exploit the main functionalities of a highly complex software system, such as a modern operating system.

To this end, we will deeply discuss the key responsibilities of so-called general purpose OSs (i.e., those typically installed on our PCs and laptops). Amongst those responsibilities are: CPU scheduling, process/thread synchronization, memory management, file systems, just to name a few. In addition, we will explore how OSs should adapt to resource-limited mobile devices (i.e., tablets and smartphones).

All the concepts introduced are totally covered by the lecture materials provided during the course, and will be treated independently from a specific operating system implementation. However, many examples will be taken from popular OSs available on the market like UNIX/Linux, Windows, macOS, Android, iOS, etc.

### Prerequisites
- Fundamentals of computer architectures
- Basics of computer programming


### Exams
TBA
<!--Per il superamento dell'esame è prevista una **prova scritta**, basata su un quiz Moodle a risposta multipla. Tutti coloro che superano la prova scritta con un punteggio _compreso tra **15** e **17**_ (estremi inclusi) sono ammessi, nonché **obbligati**, a sostenere la successiva **prova orale**. Coloro che, invece, ottengono un punteggio sufficiente (_maggiore o uguale a **18**_) alla prova scritta possono decidere di confermare il voto ottenuto **oppure** sostenere un'ulteriore prova orale integrativa opzionale.-->

### Recommended Textbooks
Despite they are not mandatory for successfully pass the exam, the following textbooks are really useful to anyone who wants to dig deeper into the subjects addressed in this course:
- _Operating System Concepts_ [Silberschatz _et al._];
- _Modern Operating Systems_ [Tanenbaum _et al._];
- _Operating Systems: Three Easy Pieces_ [Remzi] (<a href="http://pages.cs.wisc.edu/~remzi/OSTEP/" target="_blank">freely available online</a>).
 
<hr>

<!--
## Syllabus
**Introduzione**
- Concetti di base
- Storia dei sistemi operativi
- Relazione tra macchina fisica (HW) e sistemi operativi
- Struttura dei sistemi operativi

**Gestione dei Processi**
- Processi
- CPU Scheduling
- Threads
- Sincronizzazione
- Deadlock

**Gestione della memoria**
- Memoria principale (RAM)
- Memoria virtuale

**Gestione dei sistemi di I/O**
- Dispositivi di memoria di massa
- Interfaccia del file system
- Implementazione del file system
- Sistemi di I/O

<strike>**Concetti avanzati**</strike> (cancellato causa emergenza COVID-19)
- ~~Protezione~~
- ~~Sicurezza~~
- ~~Sistemi distribuiti~~
- ~~Sistemi per dispositivi mobili~~

<hr>

## Materiale Didattico

| Lezione \# | Data | Argomento                                     | Materiale      | 
|------------|------|-----------------------------------------------|----------------|
| Lezione 1  | 05/10/2020 | Introduzione | [slides: <a href="./lectures/slides/01_Intro.pdf" target="_blank">PDF</a>] |
| Lezione 2  | 07/10/2020 | Relazione tra Sistema Operativo e Macchina Fisica | [slides: <a href="./lectures/slides/02_OS_and_Computer_Architecture.pdf" target="_blank">PDF</a>]|
| Lezione 3 | 12/10/2020 | Struttura di un Sistema Operativo | [slides: <a href="./lectures/slides/03_OS_Structure.pdf" target="_blank">PDF</a>]|
| Lezione 4  | 14/10/2020 | Processi | [slides: <a href="./lectures/slides/04_Processes.pdf" target="_blank">PDF</a>] [<a href="./code/processes.tgz" download="processes.tgz">code</a>]|
| Lezioni 5 e 6  | 19/10/2020 - 21/10/2020 | Scheduling della CPU (1) | [slides: <a href="./lectures/slides/05_CPU_Scheduling_1.pdf" target="_blank">PDF</a>] |
| Lezioni 7 e 8 | 26/10/2020 - 28/10/2020 | Scheduling della CPU (2) | [slides: <a href="./lectures/slides/05_CPU_Scheduling_2.pdf" target="_blank">PDF</a>]|
| Lezioni 9 e 10 | 02/11/2020 - 04/11/2020 | Threads | [slides: <a href="./lectures/slides/06_Threads.pdf" target="_blank">PDF</a>] [<a href="./code/threads.tgz" download="threads.tgz">code</a>]|
| Lezioni 11 e 12 | 09/11/2020 - 11/11/2020 | Sincronizzazione tra Processi/Thread (1) | [slides: <a href="./lectures/slides/07_Synchronization_1.pdf" target="_blank">PDF</a>]|
| Lezione 13 | 16/11/2020 | Sincronizzazione tra Processi/Thread (2) | [slides: <a href="./lectures/slides/07_Synchronization_2.pdf" target="_blank">PDF</a>] [<a href="./code/synchronization.tgz" download="synchronization.tgz">code</a>]|
| Lezione 14 | 18/11/2020 | Deadlock | [slides: <a href="./lectures/slides/08_Deadlock.pdf" target="_blank">PDF</a>] |
| Lezione 15 | 23/11/2020 | Gestione della Memoria (1) | [slides: <a href="./lectures/slides/09_Memory_Management.pdf" target="_blank">PDF</a>] |
| Lezione 16 | 25/11/2020 | Gestione della Memoria (2) | [slides: <a href="./lectures/slides/10_Memory_Management_Paging.pdf" target="_blank">PDF</a>] |
| Lezioni 17 - 18 | 30/11/2020 - 02/12/2020 | Memoria Virtuale | [slides: <a href="./lectures/slides/11_Virtual_Memory.pdf" target="_blank">PDF</a>] |
| Lezioni 19 - 20 | 07/12/2020 - 09/12/2020 | Dispositivi di Memoria di Massa | [slides: <a href="./lectures/slides/12_Mass_Storage.pdf" target="_blank">PDF</a>] |
| Lezione 21 | 14/12/2020 | File System: Interfaccia e Implementazione | [slides: <a href="./lectures/slides/13_File_System.pdf" target="_blank">PDF</a>] |
| Lezioni 22 - 23 - 24 | 16/12/2020 - 21/12/2020 - 23/12/2020 | Esercitazioni | |

# Anni Precedenti
In questa sezione è possibile accedere alle informazioni del corso relativamente agli anni accademici precedenti rispetto a quello corrente.

**NOTA:** _La directory che include il materiale didattico è **unica** e il suo contenuto può subire modifiche o aggiornamenti di anno in anno; pertanto, è possibile che vi siano discrepanze tra ciò che è presente su questo sito e ciò che invece è stato mostrato in un determinato anno, diverso da quello corrente._

-->
