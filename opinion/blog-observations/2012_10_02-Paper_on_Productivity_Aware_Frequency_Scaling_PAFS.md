# Paper: Productivity-Aware Frequency Scaling (PAFS)

_by Lesandro Ponciano / October 02, 2012 at 03:57PM_
 
["Energy Efﬁcient Computing through Productivity-Aware Frequency Scaling"](https://doi.org/10.1109/CGC.2012.59) paper by Lesandro Ponciano, Andrey Brito, Lívia Sampaio and Francisco Brasileiro. This paper has been accepted for publication and will appear in the proceedings of the 2nd International Conference on Cloud and Green Computing (CGC 2012).
 
**Abstract** :_This paper proposes a new policy for dynamic frequency scaling: productivity-aware frequency scaling (PAFS). PAFS aims at optimizing energy consumption while still satisfying the performance requirements of a given application. In contrast to the commonly-used ondemand frequency scaling, PAFS may keep the processor in a power-save state even in high CPU-usage situations. This will be the case as long as the application (or set of applications) for which productivity is to be preserved presents acceptable performance (e.g., as established by a QoS contract). Our experiments show savings of up to 23.65% in energy consumption when compared to the commonly used ondemand DFS policy with no performance degradation for the productivity metric. PAFS is, therefore, bound to a single or a set of applications running in a machine. Nevertheless, compared to previous approaches to applicationspeciﬁc frequency scaling, PAFS does not require modifying the application or a calibration process. PAFS requires only a productivity metric which may already be exported by an application (e.g., through a log ﬁle, such as response time or throughput in an Apache webserver) or which may be computed through a simple program or script._


