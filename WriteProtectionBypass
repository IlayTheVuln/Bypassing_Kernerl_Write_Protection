//code snippet to turn of CRO bit 16-WP(write protection)
void TurnWriteProctetionOff()
{
	__asm
	{
		push eax
		mov eax, CR0
		and eax, 0111111111111111b
		mov CR0, eax
		pop eax
	}
}

//code snippet to turn on CRO bit 16 in order to turn back on write protection
void TurnWriteProtectionOn()
{
	__asm
	{
		push edx
		mov edx, CR0
		or edx, 1000000000000000b
		mov CRO,edx
		pop edx
	}
}
