### Minu Jin
+ s9430939@naver.com
+ Interest: Linux Kernel
+ Language: C

### Kernel Contribution
1. mm_release()동작 검증 -> 동작을 명확히 설명하는 주석으로 교체 ✅ (Signed-off-by Andrew Morton)

https://git.kernel.org/pub/scm/linux/kernel/git/akpm/mm.git/commit/?h=mm-nonmm-unstable&id=f34e19c34e4e92338d2ceaab2b95dd7790d262de

2. PTR_ALIGN 사용을 통한 포인터 정렬 코드 개선 ✅ (Signed-off-by Greg KH)

https://git.kernel.org/pub/scm/linux/kernel/git/gregkh/staging.git/commit/?h=staging-next&id=69dc48dc550640b1c33e30f32620fe5ef1b068e9

3. fix unchecked return value of skb_copy_bits ⏳

https://lore.kernel.org/all/20260120025051.2843461-1-s9430939@naver.com/

4. use kzalloc directly in _rtw_zmalloc ⏳

https://lore.kernel.org/all/20260120054036.3783680-1-s9430939@naver.com/

5. fix potential race in expire_timeout_chk (race condition 가능성 Fix) ⏳

https://lore.kernel.org/linux-staging/aXjwRsm7NhRpyWJH@JMW-Ubuntu/T/#t

6. copy_mm() 동작 검증 -> 동작 명확히 설명하는 주석으로 교체 ⏳

https://lore.kernel.org/all/20260127055321.2400480-1-s9430939@naver.com/

7. 오타 수정 및 printk 커널로그 pr_err현대화 ⏳

https://lore.kernel.org/all/20260102062759.3749606-1-s9430939@naver.com/

8. 헬퍼 함수 도입을 통한 레지스터 접근 리팩토링 ⏳

https://lore.kernel.org/all/20260113133831.3422480-2-s9430939@naver.com/

9. 연속 I/O 함수 도입을 통한 데이터 전송 로직 현대화 ⏳

https://lore.kernel.org/all/20260113133831.3422480-3-s9430939@naver.com/
