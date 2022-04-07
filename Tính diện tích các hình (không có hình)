Program TINH_DIEN_TICH;
Uses crt;
Procedure HV;
  Var s,a:real;
  Begin
      Writeln('TINH DIEN TICH HINH VUONG:');
      Write('Nhap chieu dai cua canh a:');readln(a);
      s:=a*a;
     Writeln('Dien tich hinh vuong = ',s:6:2);
  End;
Procedure HT;
Var s,r:real;
Begin
     Write('Nhap ban kinh R: ');readln(r);
     s:=pi*r*r;
     Writeln('Dien tich hinh tron = ',s:6:2);
End;
Procedure TG;
Var a, b, c, s, p, h:real;
    i,j:integer;
 Begin
    Writeln('TINH DIEN TICH TAM GIAC:');
    Write('Nhap canh ben 1 neu khong co nhap = 0:');readln(a);
    Write('Nhap canh ben 2 neu khong co nhap = 0:');readln(b);
    Write('Nhap canh day:');readln(c);
    write('Nhap duong cao neu khong co nhap = 0:'); readln(h);
    If ((a+b)>c)and((b+c)>a)and((a+c)>b) then
    Begin
         p:=(a+b+c)/2;
         s:=sqrt(p*(p-a)*(p-b)*(p-c)); end; begin s:=(h*c)/2; end;
         Writeln('Dien tich tam giac = ',s:4:2);
End;
Procedure CN;
Var a, b, s:real;
Begin
     Writeln('TINH DIEN TICH HINH CHU NHAT:');
     Write('Nhap chieu dai a:');readln(a);
     Write('Nhap chieu rong b:');readln(b);
     s:= a*b;
     Writeln('Dien tich hinh chu nhat = ',s:6:2);
End;
procedure  HThang;
Var a,b,c, S:real;
Begin
   Writeln('TINH DIEN TICH HINH THANG:');
   write('nhap do dai cua day lon:');readln(a);
   write('nhap do dai cua day nho:');readln(b);
   write('nhap do dai cua chieu cao:');readln(c);
   S:= ((a+b)*c)/2;
   write('Dien tich hinh thang = ',s);
End;
Procedure menu;
Var d:integer;
Begin
     Clrscr;
     Writeln('CHON MOT TRONG CAC PHUONG AN SAU:');
     Writeln('----------------------------------');
     Writeln('0: Quay ve man hinh soan thao');
     Writeln('1: Tinh dien tich hinh vuong');
     Writeln('2: Tinh dien tich hinh tron');
     Writeln('3: tinh dien tich tam giac');
     Writeln('4: Tinh dien tich hinh chu nhat');
     Writeln('5: Tinh dien tich hinh thang');
     Writeln('====================');
     Write('Hay chon mot phuong an:'); readln(d);
     Writeln('====================');
     Writeln;
   Case d of
       0: Exit;
       1: HV;
       2: HT;
       3: TG;
       4: CN;
       5: HThang;
    End;
End;
Begin
     menu;
    Readln;
End.
