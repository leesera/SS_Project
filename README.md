TODO
======

1. device_database/db_init.sql

    기본이 되는 kernel 함수들 중국 폰 모델 별로 정리<br/>
    prepare_kernel_cred, commit_creds, remap_pfn_range, ptmx_fops, perf_swevent_enabled ,security_remap_pfn_range함수 주소<br/>
    stagefright 용 libc 함수 offset <- 이건 노가다 일듯 나중에 같이 고고<br/>

    mprotect_liboffset<br/>
      restore_core_regs_liboffset<br/>
      ppr_liboffset (pop_pc)<br/>
    pppppr_liboffset (pop_r0_r1_r2_r3_r4_pc)<br/>

  각각 device들 정보들<br/>
  ro.product.model ro.build.display.id 로 구분<br/>
  'ZTE Blade G’ , 'ZTE Blade G V10.0'<br/>

2. kallsym 얻는 방법

  내용 설명

3. libexploit 부분 1805 추가 및 나머지 exploit 빼기
