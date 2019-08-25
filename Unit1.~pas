unit Unit1;

interface

uses
  Windows, Messages, SysUtils, Variants, Classes, Graphics, Controls, Forms,
  Dialogs, XPMan, StdCtrls, Buttons;

type
  TForm1 = class(TForm)
    Button1: TButton;
    Button2: TButton;
    Button3: TButton;
    Button4: TButton;
    Edit1: TEdit;
    Label1: TLabel;
    XPManifest1: TXPManifest;
    Label2: TLabel;
    BitBtn1: TBitBtn;
    Button5: TButton;
    procedure Button1Click(Sender: TObject);
    procedure Button2Click(Sender: TObject);
    procedure Button3Click(Sender: TObject);
    procedure Button4Click(Sender: TObject);
    procedure BitBtn1Click(Sender: TObject);
    procedure Button5Click(Sender: TObject);
  private
    { Private declarations }
  public
    { Public declarations }
  end;

var
  Form1: TForm1;

implementation

uses Unit2;

{$R *.dfm}

procedure TForm1.Button1Click(Sender: TObject);
var
x,y:integer;
z:double;
begin
x:= strtoint(inputbox('Toplama iþlemi için veri giriþi 1.sayý','1.sayýyý gir..',''));
y:=strtoint(inputbox('Toplama iþlemi için veri giriþi 2.sayý','2.sayýyý gir..',''));
 z:=x+y;
 showmessage (('==>   ')+floattostr(z)+('  <== '));
edit1.Text:=floattostr(z);
label1.Caption:=inttostr(x)+' + '+inttostr(y)+ ' = '+floattostr(z);
 end;

procedure TForm1.Button2Click(Sender: TObject);
var
x,y:integer;
z:double;
begin
x:= strtoint(inputbox('Çýkartma iþlemi için veri giriþi 1.sayý','1.sayýyý gir..',''));
y:=strtoint(inputbox('Çýkartma iþlemi için veri giriþi 2.sayý','2.sayýyý gir..',''));
 z:=x-y;
 showmessage (('==>   ')+floattostr(z)+('  <== '));
edit1.Text:=floattostr(z);
label1.Caption:=inttostr(x)+' - '+inttostr(y)+ ' = '+floattostr(z);

end;

procedure TForm1.Button3Click(Sender: TObject);
var
x,y:integer;
z:double;
begin
x:= strtoint(inputbox('Çarpma iþlemi için veri giriþi 1.sayý','1.sayýyý gir..',''));
y:=strtoint(inputbox('Çarpma iþlemi için veri giriþi 2.sayý','2.sayýyý gir..',''));
 z:=x*y;
 showmessage (('==>   ')+floattostr(z)+('  <== '));
edit1.Text:=floattostr(z);
label1.Caption:=inttostr(x)+' * '+inttostr(y)+ ' = '+floattostr(z);

end;

procedure TForm1.Button4Click(Sender: TObject);
var
x,y:integer;
z:double;
begin
x:= strtoint(inputbox('Bölme iþlemi için veri giriþi 1.sayý','1.sayýyý gir..',''));
y:=strtoint(inputbox('Bölme iþlemi için veri giriþi 2.sayý','2.sayýyý gir..',''));
 z:=x/y;
 showmessage (('==>   ')+floattostr(z)+('  <== '));
edit1.Text:=floattostr(z);
label1.Caption:=inttostr(x)+' / '+inttostr(y)+ ' = '+floattostr(z);

end;

procedure TForm1.BitBtn1Click(Sender: TObject);
begin
form2.show;
end;

procedure TForm1.Button5Click(Sender: TObject);
begin
close;
end;

end.
