#================================================================================
#
#    hcdiag/src/tests/CMakeLists.txt
#
#  © Copyright IBM Corporation 2015,2016. All Rights Reserved
#
#    This program is licensed under the terms of the Eclipse Public License
#    v1.0 as published by the Eclipse Foundation and available at
#    http://www.eclipse.org/legal/epl-v10.html
#
#    U.S. Government Users Restricted Rights:  Use, duplication or disclosure
#    restricted by GSA ADP Schedule Contract with IBM Corp.
#
#================================================================================

add_subdirectory(chk-cpu)
add_subdirectory(chk-cpu-count)
add_subdirectory(chk-csm-health)
add_subdirectory(chk-gpfs-mount)
add_subdirectory(chk-hca-attributes)
add_subdirectory(chk-ib-pcispeed)
#add_subdirectory(chk-kworker)
add_subdirectory(chk-led)
add_subdirectory(chk-load)
add_subdirectory(chk-mlnx-pci)
add_subdirectory(chk-nvidia-clocks)
add_subdirectory(chk-nvidia-smi)
add_subdirectory(chk-nvidia-vbios)
add_subdirectory(chk-nvme-mount)
add_subdirectory(chk-nvme)
add_subdirectory(chk-os)
add_subdirectory(chk-sys-firmware-local)
add_subdirectory(chk-sys-firmware)
add_subdirectory(chk-zombies)
add_subdirectory(common)
add_subdirectory(daxpy)
add_subdirectory(dcgm-diag)
add_subdirectory(dcgm-health)
add_subdirectory(dgemm)
add_subdirectory(dgemm-gpu)
add_subdirectory(fieldiag)
add_subdirectory(gpfsperf)
add_subdirectory(gpu-health)
add_subdirectory(hxecache)
add_subdirectory(hxecpu)
add_subdirectory(hxeewm)
add_subdirectory(hxediag)
add_subdirectory(hxefabricbus)
add_subdirectory(hxefpu64)
add_subdirectory(hxemem64)
add_subdirectory(hxenvidia)
add_subdirectory(hxerng)
add_subdirectory(hxestorage)
add_subdirectory(hxesctu)
add_subdirectory(ipoib)
add_subdirectory(jlink)
add_subdirectory(nvvs)
add_subdirectory(p2pBandwidthLatencyTest)
add_subdirectory(ppping)
add_subdirectory(rpower)
add_subdirectory(rvitals)
add_subdirectory(temp)
add_subdirectory(test_simple)
add_subdirectory(test_memsize)
#add_subdirectory(test_2)
