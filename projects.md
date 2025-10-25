# Projects

[Home](./README.md) | [About](./README.md#about) | [Education](./education.md) | [Experience](./experience.md) | [Publications](./publications.md) | [Projects](./projects.md) | [Skills](./skills.md) | [Awards](./awards.md) | [Resume](./resume.md)

---

## High-Performance Computing Projects

### Parallelized Game of Life
**Technologies**: C++, MPI, Kokkos  
**Focus**: Distributed & Parallel Computing

#### Overview
Developed a highly scalable implementation of Conway's Game of Life using a 2D domain decomposition strategy. This project demonstrates expertise in both distributed and shared-memory parallel programming paradigms.

#### Key Features
- **Distributed Communication**: Leveraged MPI for efficient cross-node message passing and boundary exchange
- **On-Node Parallelism**: Utilized Kokkos for portable performance across different architectures (CPUs, GPUs)
- **2D Decomposition**: Implemented efficient domain partitioning for load balancing
- **Scalability**: Designed to scale from single workstations to large HPC clusters

#### Technical Highlights
- Ghost cell exchange using non-blocking MPI communication
- Performance-portable code that runs on multiple architectures
- Optimized memory access patterns for cache efficiency
- Strong and weak scaling analysis

**Repository**: [GitHub Link](#)

---

## Systems Programming Projects

### CMU BusTub Database Engine
**Technologies**: C++, Makefile  
**Focus**: Database Systems & Memory Management

#### Overview
Contributed to CMU's educational database system (BusTub) by implementing core components of a relational database engine, focusing on buffer management and page replacement strategies.

#### Key Components Implemented

**Buffer Pool Manager**
- Efficient memory management for database pages
- Page pinning and unpinning mechanisms
- Integration with disk manager for page I/O
- Thread-safe operations using latches

**LRU Page Replacement Algorithm**
- Thread-safe implementation of Least Recently Used policy
- Optimized for minimal lock contention
- Maximizes buffer pool hit rate
- Efficient eviction of cold pages

#### Learning Outcomes
- Deep understanding of database internals
- Experience with concurrent data structures
- Memory management best practices
- Systems-level C++ programming

**Repository**: [GitHub Link](#)

---

## Graduation Project

### Blogram - Instagram for the Visually Impaired
**Technologies**: Go, AWS, Machine Learning APIs  
**Achievement**: Excellence with Honor  
**Team Size**: 4 members

#### Project Vision
Created an accessible social media platform specifically designed for blind and visually impaired users, making visual content accessible through audio descriptions and voice commands.

#### Key Features

**Image Captioning**
- Automatic generation of detailed image descriptions
- Integration with ML models for accurate scene understanding
- Context-aware captions considering social media context

**Voice-Controlled Navigation**
- Complete hands-free app navigation
- Natural language command processing
- Audio feedback for all interactions

**Social Features**
- Connect with friends and family
- Real-time chat with text-to-speech
- Audio posts and voice messages
- Accessible feed browsing

**Accessibility-First Design**
- Screen reader optimization
- High-contrast UI options
- Customizable audio speed and voice
- Haptic feedback integration

#### Technical Architecture
- **Backend**: Go microservices architecture
- **Cloud Infrastructure**: AWS (EC2, S3, Lambda)
- **ML Services**: Image captioning and object detection
- **Database**: PostgreSQL for user data
- **Real-time Communication**: WebSocket for chat

#### My Contributions
- Architected the complete system design
- Led the deployment and DevOps strategy
- Designed core backend components
- Implemented CI/CD pipeline on AWS

**Impact**: Demonstrated commitment to inclusive technology and accessibility

---

## Distributed Systems Projects

### Distributed Word Matcher
**Technologies**: Go  
**Course**: Princeton University - Distributed Systems  
**Focus**: Concurrency & Parallel Processing

#### Overview
Implemented an efficient distributed system for identifying the most common words across large text corpora using Go's concurrency primitives.

#### Technical Implementation
- **Goroutines**: Spawned multiple concurrent workers for parallel processing
- **Channels**: Used for safe communication between workers
- **Work Distribution**: Implemented dynamic load balancing across workers
- **Aggregation**: Efficient merging of results from multiple workers

#### Key Concepts Demonstrated
- Go concurrency patterns (fan-out/fan-in)
- Channel-based synchronization
- Work stealing for load balancing
- Race-free concurrent map access

#### Performance Results
- Linear speedup with number of workers (up to hardware limit)
- Efficient CPU utilization across all cores
- Minimal synchronization overhead

**Repository**: [GitHub Link](#)

---

## Earlier Projects

### M3ntorship Backend Platform
**Technologies**: Nest.js, GitHub Actions, PostgreSQL  
**Role**: Backend Engineering Intern

- Co-designed microservices architecture from scratch
- Implemented RESTful API endpoints for mentor-mentee matching
- Automated CI/CD pipeline using GitHub Actions
- Designed database schema and relationships

---

## Open Source Contributions

Interested in contributing to:
- HPC libraries and tools (MPI, Kokkos, RAJA)
- Performance analysis tools (rocPROF, PAPI)
- Database systems (PostgreSQL, distributed databases)

---

## Future Projects

Areas I'm interested in exploring:
- Custom GPU kernels for specialized workloads
- Performance analysis tools for heterogeneous systems
- Distributed training frameworks for large models
- Memory-disaggregated computing systems

---

[← Back to Main Page](./README.md)
