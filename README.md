# SF-Rec
\begin{table}[H]
\caption{Recommended performance for different models}
\centering
\resizebox{\textwidth}{!}{ 
\begin{tabular}{|l|c|c|c|c|c|c|c|c|c|c|}
\hline
Dataset & metrics & SASRec & FEARec & SASRecF & FDSA & DIF-SR & UniSRec & SMLP4Rec & TedRec & ours \\ \hline
\multirow{ml-1m} & R@10   & 0.2300 & 0.2407 & 0.2356 & 0.2286 & 0.2313 & 0.2257 & 0.2157 & \underline{0.2566} & \textbf{0.2648} \\ \cline{2-11}
                       & R@20   & 0.3439 & 0.3549 & 0.3515 & 0.3435 & 0.3507 & 0.3474 & 0.3346 & \underline{0.3669} & \textbf{0.3792} \\ \cline{2-11}
                       & N@10   & 0.1146 & 0.1258 & 0.1249 & 0.1170 & 0.1164 & 0.1140 & 0.1107 & \underline{0.1415} & \textbf{0.1446} \\ \cline{2-11}
                       & N@20   & 0.1433 & 0.1554 & 0.1541 & 0.1460 & 0.1464 & \underline{0.1146} & 0.1407 & 0.1693 & \textbf{0.1732} \\ \hline
\multirow{OR}    & R@10   & 0.1545 & 0.1532 & 0.1479 & 0.1491 & 0.1522 & 0.1526 & 0.1515 & \underline{0.2222} & \textbf{0.2253} \\ \cline{2-11}
                       & R@20   & 0.2496 & 0.2509 & 0.2344 & 0.2369 & 0.2478 & 0.2421 & 0.2508 & \underline{0.3090} & \textbf{0.3134} \\ \cline{2-11}
                       & N@10   & 0.0699 & 0.0775 & 0.0744 & 0.0709 & 0.0708 & 0.0717 & 0.0650 & \underline{0.1308} & \textbf{0.1322} \\ \cline{2-11}
                       & N@20   & 0.0939 & 0.0971 & 0.0962 & 0.0931 & 0.0948 & 0.0943 & 0.0901 & \underline{0.1527} & \textbf{0.1546} \\ \hline
\multirow{Office} & R@10   & 0.1061 & 0.1172 & 0.1081 & 0.1111 & 0.1162 & 0.1233 & 0.1183 & \underline{0.1359} & \textbf{0.1387} \\ \cline{2-11}
                       & R@20   & 0.1272 & 0.1418 & 0.1276 & 0.1329 & 0.1406 & 0.1510 & 0.1483 & \underline{0.1600} & \textbf{0.1653} \\ \cline{2-11}
                       & N@10   & 0.0699 & 0.0757 & 0.0841 & 0.0851 & 0.0783 & 0.0723 & 0.0700 & \underline{0.1049} & \textbf{0.1073} \\ \cline{2-11}
                       & N@20   & 0.0753 & 0.0792 & 0.0890 & 0.0906 & 0.0840 & 0.0792 & 0.0776 & \underline{0.1107} & \textbf{0.1137} \\ \hline
\end{tabular}
}
\label{tab:metrics_comparison} 
\end{table}

