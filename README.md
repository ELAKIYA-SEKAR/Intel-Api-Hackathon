# Intel-Api-Hackathon
A multimodal mental health assessment suite combines video, audio, and NLP analysis to understand emotions, speech patterns, and written responses for accurate diagnostics and treatment planning, addressing rising mental health concerns.
Team Name - Lannister Lions
Problem Statement - Generative AI Large Language Models Fine Tuned For Legal Practice Platform
Team Leader Email - Nikhil Bansal
A Brief of the Prototype:
The platform seamlessly integrates the capabilities of oneAPI and Intel technologies to empower legal professionals with advanced tools. Lawyers, upon login, gain access to a personalized dashboard presenting a detailed profile summary, including statistics on cases won, cases lost, and ongoing cases. Leveraging the Retrieval-Augmented Generation (RAG) technique backed by oneAPI, specific cases unfold with context-rich information, enhancing the lawyer's insights.

Furthermore, a sophisticated chat module, underpinned by our finely-tuned LLAMA-2 model and powered by Intel technologies, facilitates technical discussions on legal matters. The integration of oneAPI ensures optimized performance, scalability, and efficiency throughout the platform. This technical synergy of oneAPI, Intel technologies, RAG, and LLAMA-2 not only elevates the lawyer's ability to efficiently manage cases but also establishes a secure and technologically advanced environment for legal practitioners.

Tech Stack:
Intel® oneAPI Deep Neural Network Library (oneDNN):

Use oneDNN for optimized deep learning operations, accelerating the training and inference processes of the fine-tuned LLAMA-2 model.
import onednnSave
Intel® oneAPI Math Kernel Library (oneMKL):

Leverage oneMKL for optimized mathematical operations, improving the overall performance of machine learning algorithms and computations.
import mkl
Intel® oneAPI Threading Building Blocks (oneTBB):

Employ oneTBB for efficient parallelism in indexing, retrieval, and other parallelizable tasks, enhancing the scalability of the platform.
#include <tbb>
Intel® oneAPI Data Parallel C++ (oneAPI DPC++):

Use oneAPI DPC++ for parallel execution of natural language processing tasks, optimizing query understanding and expansion.
#include <CL/sycl.hpp>
Intel® oneAPI Security Libraries:

Incorporate oneAPI security libraries to implement robust security measures for safeguarding sensitive legal information.
#include <ippcp.h>
