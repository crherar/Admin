.include <bsd.own.mk>

SUBDIR+=	ds input pm rs sched vfs vm manager sched_rr sched_fcfs

.if ${MKIMAGEONLY} == "no"
SUBDIR+=	ipc is devman
.endif

.include <bsd.subdir.mk>
