>#What is FDC?
>>Wang Qubi (FDC) is an encrypted currency such as bitcoin, although it does not use SHA256 as its work proof (POW). From Tenebrix and Litecoin to get development clues, FDC is currently using a simplified version of scrypt. Http://www.gogolm2018.com/ License - license license (FDC) is issued according to the MIT license terms. For more information, see COPYING or refer to http://opensource.org/licenses/MIT. The development and contribution of -JAGEX developers in 2017 was developed by anonymous organizations. The new development work is in progress. The development team and other volunteers can work freely in their own trees, and submit requests when function or error repair is ready. The total output will be set to  `1200000000 FDC`. The version policy version number follows the major.minor.patch semantics. There are 3 types of branches in this repository: • master: stable, the latest version of the latest major.minor version. • maintenance: stability, including the latest version of the previous version that is still being actively maintained. Format: -maint. Development: unstable, including the new code of the planned version. Format: -dev The Master and maintenance branches can be modified by publication. The planned version will always have a development branch and should submit requests for these branches. The maintenance branch is only suitable for error repair. Please submit new features for the highest version of the development branch. How many FDC is there to have a common problem? - too many puppies!  How to get FDC? The simplified variant of the scrypt key derived function is used as proof of the operation of Wang Qu currency, and the target time of each block is one minute, after which each block is hard to readjust. The block rewards are fixed, each of which is reduced by 100000. From sixtieth million yuan, each bonus of 10000 rupees will be paid. At first, a different payment scheme was conceived. The maximum reward was obtained according to the block schedule, and the number of the 0 and the largest reward was obtained by the result of the Mason internal distortion pseudorandom number generator to determine the block reward. From the 145 thousand, this has changed to prevent large game pool game systems and to excavate high reward blocks. Meanwhile， The current incentive plan: 1-99999:0-1000000 100000-144999:0-500000 Wang Wang Qu coin currency 145000-199999:250000 200000-299999:125000 currency interest interest interest Wang Wang Wang Wang 400000-499999:31250 300000-399999:62500 coin coin coin 500000-599999:15625 fun fun fun fun coin coin 600000+:10000 Wang Wang first incentive plan, including the group target one minute and four hours of difficult adjustment: 1-99999:0-1000000 Wang 100000-199999:0-500000 Wang 200000-299999:0-250000 currency interest interest currency 300000-399999:0-125000 Wang Wang fun coin currency 400000-499999:0-62500 500000-599999:0-31250 currency interest interest interest Wang Wang Wang coin currency 600000+:12000000 (FDC). Make woof money / in-cli / Wang interest -qt The following is a developer note on how to build a WAN on your local platform. They are not a complete guide, but they include notes on the necessary libraries, compiling symbols, and so on. • OSX construction instructions, Unix construction instructions, Windows construction instructions Such a port RPC 22555 P2P 22556 The changes in translation and the new translation can be submitted to the Transifex page of Bitcoin Core. The translation is extracted from Transifex regularly and merged into the GIT repository. Please refer to the translation process to get detailed information about how to work. If these changes are specific to the Wang interest currency, they can be submitted as a pull request for the repository. If it is a general translation, please consider the upstream submission, because we will provide these changes later. The development policy for debugging is compiled using the --enable-debug option to run configure, and then make. Or run configure with CXXFLAGS = "- G -ggdb -O0" or any debug flag you need. If the debug.log code abnormal behavior, please see the data directory of the debug.log file; error writing and debugging messages in there. -debug =... Command line options control debugging; -debug operation will open in all categories (and very large debug.log files for you). The Qt code routes the qDebug () output to the debug.log under category "QT": use -debug = QT to run to view it. Testnet and regtest mode if you are testing need to be interconnected
