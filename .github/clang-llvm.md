## RESOURCES for Clang & LLVM
- use llvm to develop a new programming language, see this [page](http://llvm-tutorial-cn.readthedocs.io/en/latest/index.html) and the original source [page](http://llvm.org/docs/tutorial/index.html)
- Filesystem Hierarchy Standard, see this [page](http://www.pathname.com/fhs/pub/fhs-2.3.html)
- CSc 453: Compilers and Systems Software, see this [PAGE](https://www2.cs.arizona.edu/classes/cs453/fall15/)
- CMU, CS745, Optimizing Compiler, see this [repo](http://www.cs.cmu.edu/afs/cs/academic/class/15745-s13/public/) and its course [page](http://www.cs.cmu.edu/afs/cs.cmu.edu/academic/class/15745-s13/www/)
- CMU, linker basic concepts, see this [PAGE](https://www.cs.cmu.edu/afs/cs/academic/class/15213-f10/www/lectures/11-linking.pdf)
- NYU，Compiler Construction， G22.2130.01，checkout this [PAGE](http://cs.nyu.edu/courses/fall04/G22.2130-001/)
- Tutorial: Creating an LLVM Backend for the Cpu0 Architecture, checkout this [PAGE](https://jonathan2251.github.io/lbd/)
- Uppsala University Department of Information Technology, [Advanced Compiler Design](http://user.it.uu.se/~kostis/Teaching/KT2-06/)
- for `linux inside`, you can checkout this [PAGE](https://0xax.gitbooks.io/linux-insides/content/)
- UCSD, CSE 231: Advanced Compilers, checkout this [PAGE](https://cseweb.ucsd.edu/classes/sp14/cse231-a/index.html)
- CMU, 15-411: Compiler Design, see this [PAGE](https://www.cs.cmu.edu/~fp/courses/15411-f08/index.html)
- A very nice website that introduces `The Architecture of Open Source Applications`, for more details checkout this [PAGE](http://www.aosabook.org/en/index.html), LLVM can be found [here](http://www.aosabook.org/en/llvm.html)
- For MIPS architecture, checkout the book < `See MIPS Run` > and its ABI document, see this [PAGE](https://www.linux-mips.org/pub/linux/mips/doc/ABI/)
- A short tutorial for latex, see this [page](http://www.mohu.org/info/lshort-cn.pdf) & a tiny book about `awk` checkout this [page](http://awk.readthedocs.io/en/latest/index.html)
- A nice book about open-source project, <Producing Open Source Software: How to Run a Successful Free Software Project>, checkout this [page](https://producingoss.com)
- some free tech book website, checkout this [page](http://www.freetechbooks.com/)
- A nice website about open-source, checkout this [page](http://www.open-open.com/)
- For gnu project website, you can checkout this [page](https://sourceware.org/), e.g., gnu `as` assembler in the binutils, see this [page](https://sourceware.org/binutils/docs-2.29/as/index.html)
- For github upload size limit soulution, you can checkout this [page](https://help.github.com/articles/removing-sensitive-data-from-a-repository/)
- :+1: Compiler profiling, basics see [here](http://www.embecosm.com/appnotes/ean6/html/ch07s03s03.html) and LLVM profiling see [here](http://llvm.org/pubs/2010-04-NeustifterProfiling.pdf)
- Linux `profiling and optimization` see Princeton's [slides](https://www.cs.princeton.edu/picasso/mats/mats_S07/Lucifredi_Lecture_Feb07.pdf)
- LLVM metadata expansion IR, chkectout LLVM blog page, [Extensible Metadata in LLVM IR](http://blog.llvm.org/2010/04/extensible-metadata-in-llvm-ir.html) and LLVM official langref [page](http://llvm.org/docs/LangRef.html), github page [TypeMetadata.rst](https://github.com/llvm-mirror/llvm/blob/master/docs/TypeMetadata.rst), csdn [blog](http://blog.csdn.net/dreammeard/article/details/19493599)
- CUDA NVPTX backend info of `kernel` keyword, see this [page](http://llvm.org/docs/NVPTXUsage.html#conventions)
- tmux tips, checkout this [blog](http://blog.csdn.net/simple_the_best/article/details/51360778)
- clang attribute metadata see [how to change clang](https://github.com/llvm-mirror/clang/blob/master/docs/InternalsManual.rst#how-to-change-clang), while for CUDA NVPTX backend info of `kernel` keyword, see NVPTXUage [page](http://llvm.org/docs/NVPTXUsage.html#conventions)
- [rsync resume after being interrupted](https://unix.stackexchange.com/questions/48298/can-rsync-resume-after-being-interrupted) and [broken pipe](https://askubuntu.com/questions/127369/how-to-prevent-write-failed-broken-pipe-on-ssh-connection)
- spend some time reading the src of clang & llvm
- Linux remote desktop software, see [here](https://www.nomachine.com/DT07M00078) and its remote desktop environment, checkout this [page](https://www.nomachine.com/AR07K00676)
- how to generate `ManPage` on linux-like system, checkout this [page](http://www.linuxjournal.com/content/creating-custom-man-pages)
- [Create a working compiler with the LLVM framework](https://www.ibm.com/developerworks/library/os-createcompilerllvm2/index.html)
- dynamic generate or insert `globalvar` or `VarDecl` for current module, checkout these stackoverflow pages: [1](https://stackoverflow.com/questions/23328832/llvm-initialize-an-integer-global-variable-with-value-0) & [2](https://stackoverflow.com/questions/23330018/llvm-global-integer-array-zeroinitializer) 
- Clang QualType => Type, see [here](https://reviews.llvm.org/D35180)
- llvm back-end Instruction Selection DAG, see [here](http://llvm.org/devmtg/2008-08/Gohman_CodeGenAndSelectionDAGs.pdf)
- LLVM `Global Instruction Selection` see its doc [page](https://www.llvm.org/docs/GlobalISel.html) and this slide [page](http://llvm.org/devmtg/2015-10/slides/Colombet-GlobalInstructionSelection.pdf)
- [Compiler Validations](http://processors.wiki.ti.com/index.php/Compiler_Validation), and for super-test its tutorial see [here](https://marketplace.windriver.com/index.php?packages&on=details&id=69&cat=17)
- LLVM Emit an extra section with meta-information, see its [mail-list](http://llvm.1065342.n5.nabble.com/Emitting-an-extra-section-with-meta-information-td51523.html); Emit Clang version information into .comment section, see [here](https://reviews.llvm.org/D1720), class [MCStreamer](http://llvm.org/doxygen/classllvm_1_1MCStreamer.html) and [MCELFStreamer](http://www.llvm.org/doxygen/classllvm_1_1MCELFStreamer.html) and this page for [MCSection](https://www.llvm.org.cn/docs/CodeGenerator.html#the-mcsection-class) class.
- some backend implement can ref to [AMDGPU](https://github.com/llvm-mirror/llvm/tree/master/lib/Target/AMDGPU)
- difference between scratch pad and cache memory, see quora [page](https://www.quora.com/What-is-the-difference-between-scratchpad-and-cache-memories) and this [paper](https://es.cs.uni-kl.de/publications/data/Lang15.pdf)
- for llvm target global address, ref to [Purpose of MSP430Wrapper](https://groups.google.com/forum/#!topic/llvm-dev/DqICbGd0y_Y)
- PTX code generator, see this [M](http://compilers.cs.uni-saarland.de/publications/theses/rhodin_bsc.pdf)
- clang set alignment of local variable, checkout this [mail-list](http://clang-developers.42468.n3.nabble.com/alignment-of-local-variables-td2743966.html), e.g. `int a[N+1] __attribute__ ((__aligned__(16)));`
- common vector optimization, see this TACC course [page](https://portal.tacc.utexas.edu/documents/13601/1041435/06-Serial_and_Vector_Optimization.pdf/4eef1e1c-7592-4ac4-8608-1f0662553a88) and intel's dev blog <https://software.intel.com/en-us/articles/vectorization-writing-cc-code-in-vector-format>
- HCC compiler, see this intro page <http://www.open-std.org/jtc1/sc22/wg21/docs/papers/2015/p0069r0.pdf> and its gpuopen page <https://gpuopen.com/compute-product/hcc-heterogeneous-compute-compiler/>
- :thumbsdown: When you really don't know where does the data alignment at the stack come from, you can simply set it at `CodeGen` module of Clang, almost everything can be done here， though this rule may harm `modularity` of clang, but it's really useful.
- Compiler name mangling, see this [page](https://en.wikipedia.org/wiki/Name_mangling)
- Extend llvm & clang, checkout this [page](http://llvm.org/docs/ExtendingLLVM.html)
- LLVM Backends `MBlaze` (Micro Blaze), see this [page](http://legup.eecg.utoronto.ca/doxygen/dir_15f75cd5e020f3c6b1d0a91d94880675.html), it is an extention of [C51](http://www.keil.com/support/man/docs/is51/)
- More details about llvm MC Layer: <http://www.llvm.org/devmtg/2010-11/Dunbar-MC.pdf>
- These slides maybe useful, checkout this github repo: <https://github.com/azru0512/slide>
- nice github repo: <https://github.com/embecosm> & llvm `Integrated Assembler` see this page:<http://www.embecosm.com/resources/appnotes/#EAN10>
- CppCon github repo: <https://github.com/CppCon> 
- Clang OpenMP, checkout this [slide](https://llvm-hpc2-workshop.github.io/slides/Wong.pdf)
- vimrc, set whichwrap for left and right cursor, see this [page](http://vim.wikia.com/wiki/Automatically_wrap_left_and_right)
- IEEE 754, Half-precision floating point library, see this sourceforge page <http://half.sourceforge.net/index.html>
- Extend LLVM see this official page: <https://llvm.org/docs/ExtendingLLVM.html> and this page: <http://web.cs.ucla.edu/classes/spring08/cs259/llvm-2.2/docs/ExtendingLLVM.html>, this [mail list](http://clang-developers.42468.n3.nabble.com/Adding-new-data-type-td763908.html)
- Clang has already supported half type, see this [page](https://clang.llvm.org/docs/LanguageExtensions.html#half-precision-floating-point) and review list: <https://reviews.llvm.org/D9781> and OpenCL half [support](http://clang-developers.42468.n3.nabble.com/Re-LLVMdev-PATCH-OpenCL-half-support-td2565689.html)
- OpenCL support half precision floating point type literal, checkout this review changes: <https://reviews.llvm.org/D16865>
- Sharp tools make good work. LLVM vim plugin see its offical github repo: <https://github.com/llvm-mirror/llvm/tree/master/utils/vim> and this github repo: <https://github.com/Superbil/llvm.vim>, and this llvm-devmtg slide: <https://llvm.org/devmtg/2016-01/slides/ModernCplusplusDevelopment.pdf>
- Book Reading <Engineering A Compiler>, checkout Rice University, COMP 512: Advanced Compiler Construction, course page: <https://www.clear.rice.edu/comp512/>
- [ ] TODO: Spare some effort in hacking into the source code of Clang & LLVM from the perspective of `designing pattern`.
- GNU function attributes: <https://gcc.gnu.org/onlinedocs/gcc-5.3.0/gcc/Function-Attributes.html>
- Lessons to learn from the CLang/LLVM codebase: <http://cppdepend.com/blog/?p=92>
- Clang Rocks! <https://www.codeproject.com/Articles/475254/ClangplusRocks>
- Mechanism of template meta-programming, see wiki page: <https://en.wikipedia.org/wiki/Template_metaprogramming> 
- Pattern matching in programming languages, e.g. Haskell, Scalar and etc, checkout wiki page:<https://en.wikipedia.org/wiki/Pattern_matchin>
- For Mac OS git auto completion, checkout git repo page: <https://github.com/git/git/blob/master/contrib/completion/git-completion.bash#L19-L23>
- Cpp Traits: <https://accu.org/index.php/journals/442> & <https://www.ibm.com/developerworks/community/blogs/12bb75c9-dfec-42f5-8b55-b669cc56ad76/entry/c_11%25e6%25a0%2587%25e5%2587%2586%25e5%25ba%2593%25e4%25b9%258btype_traits%25e7%25ae%2580%25e4%25bb%258b?lang=en> & <http://www.bogotobogo.com/cplusplus/template_specialization_traits.php> & type traits: <http://www.drdobbs.com/cpp/c-type-traits/184404270>
- Haskell, interesting programming language: <https://www.haskell.org> and nice book: <http://readfree.me/book/25803388/>
