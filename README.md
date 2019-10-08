# research
# CVE-2019-17241
### Description
> IrfanView 4.53 allows a User Mode Write AV starting at WSQ!ReadWSQ+0x000000000000d563.
>
> ------------------------------------------
>
> [VulnerabilityType Other]
> User mode write access violations
>
> ------------------------------------------
>
> [Vendor of Product]
> Irfanview
>
> ------------------------------------------
>
> [Affected Product Code Base]
> Irfanview - 4.53
>
> ------------------------------------------
>
> [Affected Component]
> Plugin Wsq.dll read file wsq.
> WSQ!ReadWSQ+0xd563:
> 6504e5b3 660f7f07        movdqa  xmmword ptr [edi],xmm0 ds:002b:0b880000=
>
> ------------------------------------------
>
> [Attack Type]
> Local
>
> ------------------------------------------
>
> [Attack Vectors]
> to exploit vulnerability, someone must open a crafted WSQ file.
>
> ------------------------------------------
>
> [Discoverer]
> Infiniti Team, VinCSS (a member of Vingroup)
>
> ------------------------------------------
>
> [Reference]
> https://www.irfanview.com/main_history.htm

# CVE-2019-17242


### Description
> IrfanView 4.53 allows a User Mode Write AV starting at WSQ!ReadWSQ+0x000000000000966f.
>
> ------------------------------------------
>
> [VulnerabilityType Other]
> User mode write access violations
>
> ------------------------------------------
>
> [Vendor of Product]
> IrfanView
>
> ------------------------------------------
>
> [Affected Product Code Base]
> IrfanView - 4.53
>
> ------------------------------------------
>
> [Affected Component]
> Plugin Wsq.dll read file wsq.
> WSQ!ReadWSQ+0x966f:
> 657aa6bf f3ab            rep stos dword ptr es:[edi]
>
> ------------------------------------------
>
> [Attack Type]
> Local
>
> ------------------------------------------
>
> [Attack Vectors]
> to exploit vulnerability, someone must open a crafted WSQ file.
>
> ------------------------------------------
>
> [Discoverer]
> Infiniti Team, VinCSS (a member of Vingroup)
>
> ------------------------------------------
>
> [Reference]
> https://www.irfanview.com/main_history.htm


# CVE-2019-17243

# Description
> IrfanView 4.53 allows Data from a Faulting Address to control Code Flow starting at JPEG_LS+0x0000000000003155.
>
> ------------------------------------------
>
> [VulnerabilityType Other]
> The data from the faulting address is later used as the target for a branch.
>
> ------------------------------------------
>
> [Vendor of Product]
> Irfanview
>
> ------------------------------------------
>
> [Affected Product Code Base]
> irfanview - 4.53
>
> ------------------------------------------
>
> [Affected Component]
> Plugin JPEG_LS.dll read file JPEG_LS.
> JPEG_LS+0x3155:
> 6cb83155 8b16            mov     edx,dword ptr [esi]  ds:002b:00000000=
>
> ------------------------------------------
>
> [Attack Vectors]
> to exploit vulnerability, someone must open a crafted JPEG_LS file.
>
> ------------------------------------------
>
> [Discoverer]
> Infiniti Team, VinCSS (a member of Vingroup)
>
> ------------------------------------------
>
> [Reference]
> https://www.irfanview.com/main_history.htm


# CVE-2019-17244

### Description
> IrfanView 4.53 allows Data from a Faulting Address to control Code Flow starting at JPEG_LS+0x0000000000001d8a.
>
> ------------------------------------------
>
> [VulnerabilityType Other]
> The data from the faulting address is later used as the target for a branch.
>
> ------------------------------------------
>
> [Vendor of Product]
> Irfanview
>
> ------------------------------------------
>
> [Affected Product Code Base]
> irfanview - 4.53
>
> ------------------------------------------
>
> [Affected Component]
> Plugin JPEG_LS.dll read file JPEG_LS.
> JPEG_LS+0x1d8a:
> 6cb81d8a 8b16            mov     edx,dword ptr [esi]  ds:002b:00000000=
>
> ------------------------------------------
>
> [Attack Vectors]
> to exploit vulnerability, someone must open a crafted JPEG_LS file.
>
> ------------------------------------------
>
> [Discoverer]
> Infiniti Team, VinCSS (a member of Vingroup)
>
> ------------------------------------------
>
> [Reference]
> https://www.irfanview.com/main_history.htm


# CVE-2019-17245
### Description
> IrfanView 4.53 allows a User Mode Write AV starting at WSQ!ReadWSQ+0x0000000000004359.
>
> ------------------------------------------
>
> [VulnerabilityType Other]
> User mode write access violations
>
> ------------------------------------------
>
> [Vendor of Product]
> Irfanview
>
> ------------------------------------------
>
> [Affected Product Code Base]
> Irfanview - 4.53
>
> ------------------------------------------
>
> [Affected Component]
> Plugin Wsq.dll read file wsq.
> WSQ!ReadWSQ+0x4359:
> 657b53a9 8907            mov     dword ptr [edi],eax  ds:002b:0b8b4000=
>
> ------------------------------------------
>
> [Attack Type]
> Local
>
> ------------------------------------------
>
> [Attack Vectors]
> to exploit vulnerability, someone must open a crafted WSQ file.
>
> ------------------------------------------
>
> [Discoverer]
> Infiniti Team, VinCSS (a member of Vingroup)
>
> ------------------------------------------
>
> [Reference]
> https://www.irfanview.com/main_history.htm


# CVE-2019-17246
### Description
> IrfanView 4.53 allows a User Mode Write AV starting at WSQ!ReadWSQ+0x000000000000258c.
>
> ------------------------------------------
>
> [VulnerabilityType Other]
> User mode write access violations
>
> ------------------------------------------
>
> [Vendor of Product]
> Irfanview
>
> ------------------------------------------
>
> [Affected Product Code Base]
> Irfanview - 4.53
>
> ------------------------------------------
>
> [Affected Component]
> Plugin Wsq.dll read file wsq.
> WSQ!ReadWSQ+0x258c:
> 650b35dc 66897d00        mov     word ptr [ebp],di        ss:002b:0b850000=
>
> ------------------------------------------
>
> [Attack Vectors]
> to exploit vulnerability, someone must open a crafted WSQ file.
>
> ------------------------------------------
>
> [Discoverer]
> Infiniti Team, VinCSS (a member of Vingroup)
>
> ------------------------------------------
>
> [Reference]
> https://www.irfanview.com/main_history.htm


# CVE-2019-17247
### Description
> IrfanView 4.53 allows Data from a Faulting Address to control a subsequent Write Address starting at JPEG_LS+0x0000000000007da8.
>
> ------------------------------------------
>
> [VulnerabilityType Other]
> The data from the faulting address is later used as the target for a later write.
>
> ------------------------------------------
>
> [Vendor of Product]
> Irfanview
>
> ------------------------------------------
>
> [Affected Product Code Base]
> irfanview - 4.53
>
> ------------------------------------------
>
> [Affected Component]
> Plugin JPEG_LS.dll read file JPEG_LS.
> JPEG_LS+0x7da8:
> 6cb87da8 0fb741fe        movzx   eax,word ptr [ecx-2]     ds:002b:0405cc7a=
>
> ------------------------------------------
>
> [Attack Vectors]
> to exploit vulnerability, someone must open a crafted JPEG_LS file.
>
> ------------------------------------------
>
> [Discoverer]
> Infiniti Team, VinCSS (a member of Vingroup)
>
> ------------------------------------------
>
> [Reference]
> https://www.irfanview.com/main_history.htm


# CVE-2019-17248

### Description
> IrfanView 4.53 allows a User Mode Write AV starting at WSQ!ReadWSQ+0x00000000000025b6.
>
> ------------------------------------------
>
> [VulnerabilityType Other]
> User mode write access violations
>
> ------------------------------------------
>
> [Vendor of Product]
> Irfanview
>
> ------------------------------------------
>
> [Affected Product Code Base]
> Irfanview - 4.53
>
> ------------------------------------------
>
> [Affected Component]
> Plugin Wsq.dll read file wsq.
> WSQ!ReadWSQ+0x25b6:
> 657a3606 66894500        mov     word ptr [ebp],ax        ss:002b:0b7da000=
>
> ------------------------------------------
>
> [Attack Vectors]
> to exploit vulnerability, someone must open a crafted WSQ file.
>
> ------------------------------------------
>
> [Discoverer]
> Infiniti Team, VinCSS (a member of Vingroup)
>
> ------------------------------------------
>
> [Reference]
> https://www.irfanview.com/main_history.htm


# CVE-2019-17249

### Description
> IrfanView 4.53 allows a User Mode Write AV starting at WSQ!ReadWSQ+0x000000000000d57b.
>
> ------------------------------------------
>
> [VulnerabilityType Other]
> User mode write access violations
>
> ------------------------------------------
>
> [Vendor of Product]
> Irfanview
>
> ------------------------------------------
>
> [Affected Product Code Base]
> Irfanview - 4.53
>
> ------------------------------------------
>
> [Affected Component]
> Plugin Wsq.dll read file wsq.
> WSQ!ReadWSQ+0xd57b:
> 657ae5cb 660f7f4750      movdqa  xmmword ptr [edi+50h],xmm0 ds:002b:0b990000=
>
> ------------------------------------------
>
> [Attack Vectors]
> to exploit vulnerability, someone must open a crafted WSQ file.
>
> ------------------------------------------
>
> [Discoverer]
> Infiniti Team, VinCSS (a member of Vingroup)
>
> ------------------------------------------
>
> [Reference]
> https://www.irfanview.com/main_history.htm


# CVE-2019-17250

### Description
> IrfanView 4.53 allows a User Mode Write AV starting at WSQ!ReadWSQ+0x00000000000042f5.
>
> ------------------------------------------
>
> [VulnerabilityType Other]
> User mode write access violations
>
> ------------------------------------------
>
> [Vendor of Product]
> Irfanview
>
> ------------------------------------------
>
> [Affected Product Code Base]
> Irfanview - 4.53
>
> ------------------------------------------
>
> [Affected Component]
> Plugin Wsq.dll read file wsq.
> WSQ!ReadWSQ+0x42f5:
> 65035345 8917            mov     dword ptr [edi],edx  ds:002b:0b712ffe=
>
> ------------------------------------------
>
> [Attack Type]
> Local
>
> ------------------------------------------
>
> [Attack Vectors]
> to exploit vulnerability, someone must open a crafted WSQ file.
>
> ------------------------------------------
>
> [Discoverer]
> Infiniti Team, VinCSS (a member of Vingroup)
>
> ------------------------------------------
>
> [Reference]
> https://www.irfanview.com/main_history.htm


# CVE-2019-17251

### Description
> IrfanView 4.53 allows a User Mode Write AV starting at FORMATS!GetPlugInInfo+0x0000000000007d43.
>
> ------------------------------------------
>
> [VulnerabilityType Other]
> User mode write access violations
>
> ------------------------------------------
>
> [Vendor of Product]
> Irfanview
>
> ------------------------------------------
>
> [Affected Product Code Base]
> irfanview - 4.53
>
> ------------------------------------------
>
> [Affected Component]
> Plugin Formats.dll.
> FORMATS!GetPlugInInfo+0x7d43:
> 10063cd3 f3a5            rep movs dword ptr es:[edi],dword ptr [esi]
>
> ------------------------------------------
>
> [Attack Vectors]
> to exploit vulnerability, someone must open a crafted RAS file.
>
> ------------------------------------------
>
> [Discoverer]
> Infiniti Team, VinCSS (a member of Vingroup)
>
> ------------------------------------------
>
> [Reference]
> https://www.irfanview.com/main_history.htm



# CVE-2019-17252
### Description
> IrfanView 4.53 allows a User Mode Write AV starting at FORMATS!Read_BadPNG+0x0000000000000115.
>
> ------------------------------------------
>
> [VulnerabilityType Other]
> User mode write access violations
>
> ------------------------------------------
>
> [Vendor of Product]
> Irfanview
>
> ------------------------------------------
>
> [Affected Product Code Base]
> irfanview - 4.53
>
> ------------------------------------------
>
> [Affected Component]
> Plugin Formats.dll.
> FORMATS!Read_BadPNG+0x115:
> 1005aa65 c7462000000000  mov     dword ptr [esi+20h],0 ds:002b:0e314000=
>
> ------------------------------------------
>
> [Attack Vectors]
> to exploit vulnerability, someone must open a crafted PNG file.
>
> ------------------------------------------
>
> [Discoverer]
> Infiniti Team, VinCSS (a member of Vingroup)
>
> ------------------------------------------
>
> [Reference]
> https://www.irfanview.com/main_history.htm



# CVE-2019-17253
### Description
> IrfanView 4.53 allows a User Mode Write AV starting at JPEG_LS+0x000000000000a6b8.
>
> ------------------------------------------
>
> [VulnerabilityType Other]
> User mode write access violations
>
> ------------------------------------------
>
> [Vendor of Product]
> IrfanView
>
> ------------------------------------------
>
> [Affected Product Code Base]
> IrfanView - 4.53
>
> ------------------------------------------
>
> [Affected Component]
> Plugin JPEG_LS.dll read file jpeg_ls.
> JPEG_LS+0xa6b8:
> 6cb8a6b8 66894afe        mov     word ptr [edx-2],cx      ds:002b:05d02240=
>
> ------------------------------------------
>
> [Attack Vectors]
> to exploit vulnerability, someone must open a crafted JPEG_LS file.
>
> ------------------------------------------
>
> [Discoverer]
> Infiniti Team, VinCSS (a member of Vingroup)
>
> ------------------------------------------
>
> [Reference]
> https://www.irfanview.com/main_history.htm



# CVE-2019-17254
### Description
> IrfanView 4.53 allows Data from a Faulting Address to control a subsequent Write Address starting at FORMATS!Read_BadPNG+0x0000000000000101.
>
> ------------------------------------------
>
> [VulnerabilityType Other]
> The data from the faulting address is later used as the target for a later write.
>
> ------------------------------------------
>
> [Vendor of Product]
> Irfanview
>
> ------------------------------------------
>
> [Affected Product Code Base]
> irfanview - 4.53
>
> ------------------------------------------
>
> [Affected Component]
> Plugin Formats.dll.
> FORMATS!Read_BadPNG+0x101:
> 1005aa51 8b4608          mov     eax,dword ptr [esi+8] ds:002b:0e34a000=
>
> ------------------------------------------
>
> [Attack Type]
> Local
>
> ------------------------------------------
>
> [Attack Vectors]
> to exploit vulnerability, someone must open a crafted PNG file.
>
> ------------------------------------------
>
> [Discoverer]
> Infiniti Team, VinCSS (a member of Vingroup)
>
> ------------------------------------------
>
> [Reference]
> https://www.irfanview.com/main_history.htm



# CVE-2019-17255
### Description
> IrfanView 4.53 allows a User Mode Write AV starting at EXR!ReadEXR+0x0000000000010836.
>
> ------------------------------------------
>
> [VulnerabilityType Other]
> User mode write access violations
>
> ------------------------------------------
>
> [Vendor of Product]
> Irfanview
>
> ------------------------------------------
>
> [Affected Product Code Base]
> irfanview - 4.53
>
> ------------------------------------------
>
> [Affected Component]
> Plugin Exr.dll read file exr.
> EXR!ReadEXR+0x10836:
> 10011c86 66890a          mov     word ptr [edx],cx        ds:002b:0c71c000=
>
> ------------------------------------------
>
> [Attack Vectors]
> to exploit vulnerability, someone must open a crafted EXR file.
>
> ------------------------------------------
>
> [Discoverer]
> Infiniti Team, VinCSS (a member of Vingroup)
>
> ------------------------------------------
>
> [Reference]
> https://www.irfanview.com/main_history.htm



# CVE-2019-17256
### Description
> IrfanView 4.53 allows a
> User Mode Write AV starting at DPX!ReadDPX_W+0x0000000000001203.
>
> ------------------------------------------
>
> [VulnerabilityType Other]
> User mode write access violations
>
> ------------------------------------------
>
> [Vendor of Product]
> Irfanview
>
> ------------------------------------------
>
> [Affected Product Code Base]
> irfanview - 4.53
>
> ------------------------------------------
>
> [Affected Component]
> Plugin Dpx.dll read file DPX.
> DPX!ReadDPX_W+0x1203:
> 6541d593 8802            mov     byte ptr [edx],al          ds:002b:0b50d000=
>
> ------------------------------------------
>
> [Attack Vectors]
> to exploit vulnerability, someone must open a crafted DPX file.
>
> ------------------------------------------
>
> [Discoverer]
> Infiniti Team, VinCSS (a member of Vingroup)
>
> ------------------------------------------
>
> [Reference]
> https://www.irfanview.com/main_history.htm



# CVE-2019-17257
### Description
> IrfanView 4.53 allows a
> Exception Handler Chain to be Corrupted starting at EXR!ReadEXR+0x000000000002af80.
>
> ------------------------------------------
>
> [VulnerabilityType Other]
> Corruption of the exception handler chain
>
> ------------------------------------------
>
> [Vendor of Product]
> Irfanview
>
> ------------------------------------------
>
> [Affected Product Code Base]
> Irfanview - 4.53
>
> ------------------------------------------
>
> [Affected Component]
> Plugin Exr.dll read file exr.
> EXR!ReadEXR+0x2af80:
> 1002c3d0 f3a4            rep movs byte ptr es:[edi],byte ptr [esi]
>
> ------------------------------------------
>
> [Attack Vectors]
> to exploit vulnerability, someone must open a crafted EXR file.
>
> ------------------------------------------
>
> [Discoverer]
> Infiniti Team, VinCSS (a member of Vingroup)
>
> ------------------------------------------
>
> [Reference]
> https://www.irfanview.com/main_history.htm



# CVE-2019-17258
### Description
> IrfanView 4.53 allows Data from a Faulting Address to control a subsequent Write Address starting at JPEG_LS+0x000000000000839c.
>
> ------------------------------------------
>
> [VulnerabilityType Other]
> The data from the faulting address is later used as the target for a later write.
>
> ------------------------------------------
>
> [Vendor of Product]
> Irfanview
>
> ------------------------------------------
>
> [Affected Product Code Base]
> irfanview - 4.53
>
> ------------------------------------------
>
> [Affected Component]
> Plugin JPEG_LS.dll read file jpeg_ls.
> JPEG_LS+0x839c:
> 6cb8839c 0fb741fe        movzx   eax,word ptr [ecx-2]     ds:002b:bdcd32a8=
>
> ------------------------------------------
>
> [Attack Vectors]
> to exploit vulnerability, someone must open a crafted JPEG_LS file.
>
> ------------------------------------------
>
> [Discoverer]
> Infiniti Team, VinCSS (a member of Vingroup)
>
> ------------------------------------------
>
> [Reference]
> https://www.irfanview.com/main_history.htm



# CVE-2019-17259
### Description
> KMPlayer 4.2.2.31 allows a User Mode Write AV starting at utils!src_new+0x000000000014d6ee.
>
> ------------------------------------------
>
> [VulnerabilityType Other]
> User mode write access violations.
>
> ------------------------------------------
>
> [Vendor of Product]
> KMPlayer
>
> ------------------------------------------
>
> [Affected Product Code Base]
> KMPlayer - 4.2.2.31
>
> ------------------------------------------
>
> [Discoverer]
> Infiniti Team, VinCSS (a member of Vingroup)
>
> ------------------------------------------
>
> [Reference]
> http://www.kmplayer.com



#Use CVE-2019-17260
### Description
> MPC-HC through 1.7.13 allows a Read Access Violation on a Block Data Move starting at mpc_hc!memcpy+0x000000000000004e.
>
> ------------------------------------------
>
> [VulnerabilityType Other]
> This is a read access violation in a block data move
>
> ------------------------------------------
>
> [Vendor of Product]
> MPC-HC
>
> ------------------------------------------
>
> [Affected Product Code Base]
> MPC-HC - all version
>
> ------------------------------------------
>
> [Attack Type]
> Local
>
> ------------------------------------------
>
> [Has vendor confirmed or acknowledged the vulnerability?]
> true
>
> ------------------------------------------
>
> [Discoverer]
> Infiniti Team, VinCSS (a member of Vingroup)
>
> ------------------------------------------
>
> [Reference]
> https://mpc-hc.org/changelog/



# CVE-2019-17261
### Description
> XnView Classic 2.49.1 allows a User Mode Write AV starting at Xwsq+0x0000000000001e51.
>
> ------------------------------------------
>
> [VulnerabilityType Other]
> User mode write access violations
>
> ------------------------------------------
>
> [Vendor of Product]
> XnView
>
> ------------------------------------------
>
> [Affected Product Code Base]
> XnView Classic - 2.49.1
>
> ------------------------------------------
>
> [Affected Component]
> Plugin Xwsq.dll read file wsq.
> Xwsq+0x1e51:
> 10001e51 66895500        mov     word ptr [ebp],dx        ss:002b:05858000=
>
> ------------------------------------------
>
> [Attack Type]
> Local
>
> ------------------------------------------
>
> [Attack Vectors]
> to exploit vulnerability, someone must open a crafted WSQ file.
>
> ------------------------------------------
>
> [Discoverer]
> Infiniti Team, VinCSS (a member of Vingroup)
>
> ------------------------------------------
>
> [Reference]
> https://www.xnview.com/en/xnview/#changelog



# Use CVE-2019-17262
### Description
> XnView Classic 2.49.1 allows a User Mode Write AV starting at Xwsq+0x0000000000001fc0.
>
> ------------------------------------------
>
> [VulnerabilityType Other]
> User mode write access violations
>
> ------------------------------------------
>
> [Vendor of Product]
> XnView
>
> ------------------------------------------
>
> [Affected Product Code Base]
> XnView Classic - 2.49.1
>
> ------------------------------------------
>
> [Affected Component]
> Plugin Xwsq.dll read file wsq.
> Xwsq+0x1fc0:
> 10001fc0 f3ab            rep stos dword ptr es:[edi]
>
> ------------------------------------------
>
> [Attack Type]
> Local
>
> ------------------------------------------
>
> [Attack Vectors]
> to exploit vulnerability, someone must open a crafted WSQ file.
>
> ------------------------------------------
>
> [Discoverer]
> Infiniti Team, VinCSS (a member of Vingroup)
>
> ------------------------------------------
>
> [Reference]
> https://www.xnview.com/en/xnview/#changelog

