unit Unit1;

interface

uses
  Windows, Messages, SysUtils, Variants, Classes, Graphics, Controls, Forms,
  Dialogs, Menus, ExtCtrls, StdCtrls, jpeg;

type
  TForm1 = class(TForm)
    MainMenu1: TMainMenu;
    Home1: TMenuItem;
    KonsentrasiZat1: TMenuItem;
    Molaritas1: TMenuItem;
    Molalitas1: TMenuItem;
    FraksiMol1: TMenuItem;
    SifatKoligatifLarutan1: TMenuItem;
    PenurunanTekananUap1: TMenuItem;
    KenaikanTitikDidih1: TMenuItem;
    PenurunanTitikBeku1: TMenuItem;
    ekananOsmotik1: TMenuItem;
    Panel1: TPanel;
    Keluar1: TMenuItem;
    Panel2: TPanel;
    GroupBox1: TGroupBox;
    GroupBox2: TGroupBox;
    Label1: TLabel;
    Label2: TLabel;
    Edit1: TEdit;
    Edit2: TEdit;
    Button1: TButton;
    Label3: TLabel;
    Label4: TLabel;
    Label5: TLabel;
    Label6: TLabel;
    Edit3: TEdit;
    Edit4: TEdit;
    Edit5: TEdit;
    Button2: TButton;
    Label7: TLabel;
    GroupBox3: TGroupBox;
    Label8: TLabel;
    Label9: TLabel;
    Label10: TLabel;
    Edit6: TEdit;
    Edit7: TEdit;
    Edit8: TEdit;
    Button3: TButton;
    Label11: TLabel;
    GroupBox4: TGroupBox;
    Label12: TLabel;
    Label13: TLabel;
    Edit9: TEdit;
    Edit10: TEdit;
    Button4: TButton;
    Label14: TLabel;
    Label15: TLabel;
    GroupBox5: TGroupBox;
    Label16: TLabel;
    Label17: TLabel;
    Button5: TButton;
    Label18: TLabel;
    Edit11: TEdit;
    Edit12: TEdit;
    GroupBox6: TGroupBox;
    Label19: TLabel;
    Label20: TLabel;
    Label21: TLabel;
    Label22: TLabel;
    Edit13: TEdit;
    Edit14: TEdit;
    Edit15: TEdit;
    Edit16: TEdit;
    Button6: TButton;
    Label23: TLabel;
    GroupBox7: TGroupBox;
    Label24: TLabel;
    Label25: TLabel;
    Label26: TLabel;
    Label27: TLabel;
    Edit17: TEdit;
    Edit18: TEdit;
    Edit19: TEdit;
    Edit20: TEdit;
    Button7: TButton;
    Label28: TLabel;
    GroupBox8: TGroupBox;
    Label29: TLabel;
    Label30: TLabel;
    Button8: TButton;
    Edit21: TEdit;
    Edit22: TEdit;
    Label31: TLabel;
    Image1: TImage;
    procedure Keluar1Click(Sender: TObject);
    procedure Molalitas1Click(Sender: TObject);
    procedure Molaritas1Click(Sender: TObject);
    procedure FraksiMol1Click(Sender: TObject);
    procedure PenurunanTekananUap1Click(Sender: TObject);
    procedure KenaikanTitikDidih1Click(Sender: TObject);
    procedure PenurunanTitikBeku1Click(Sender: TObject);
    procedure ekananOsmotik1Click(Sender: TObject);
    procedure Home1Click(Sender: TObject);
    procedure FormCreate(Sender: TObject);
    procedure Button1Click(Sender: TObject);
    procedure Button2Click(Sender: TObject);
    procedure Button3Click(Sender: TObject);
    procedure Button4Click(Sender: TObject);
    procedure Button5Click(Sender: TObject);
    procedure Button6Click(Sender: TObject);
    procedure Button7Click(Sender: TObject);
    procedure Button8Click(Sender: TObject);
  private
    { Private declarations }
  public
    { Public declarations }
  end;

var
  Form1: TForm1;
  n1,v1,M1,massa2,Mr2,v2,M2,massa3,Mr3,mp3,molal3,nt4,np4,xt4,xp4,po5,xt5,dp5,kb6,massa6,Mr6,mp6,dt6,kf7,massa7,Mr7,mp7,dt7,M8,T8,phi8:real;

const
  R=0.082;

implementation

{$R *.dfm}

procedure TForm1.Keluar1Click(Sender: TObject);
begin
Application.Terminate;
end;

procedure TForm1.Molaritas1Click(Sender: TObject);
begin
image1.Visible:=false;
panel2.Visible:=true;
panel1.Visible:=false;
groupbox1.Visible:=true;
groupbox2.Visible:=true;
groupbox3.Visible:=false;
groupbox4.Visible:=false;
end;

procedure TForm1.Molalitas1Click(Sender: TObject);
begin
image1.Visible:=false;
panel2.Visible:=true;
panel1.Visible:=false;
groupbox1.Visible:=false;
groupbox2.Visible:=false;
groupbox3.Visible:=true;
groupbox4.Visible:=false;
end;

procedure TForm1.FraksiMol1Click(Sender: TObject);
begin
image1.Visible:=false;
panel2.Visible:=true;
panel1.Visible:=false;
groupbox1.Visible:=false;
groupbox2.Visible:=false;
groupbox3.Visible:=false;
groupbox4.Visible:=true;
end;

procedure TForm1.PenurunanTekananUap1Click(Sender: TObject);
begin
image1.Visible:=false;
panel1.Visible:=true;
panel2.Visible:=false;
groupbox5.Visible:=true;
groupbox6.Visible:=false;
groupbox7.Visible:=false;
groupbox8.Visible:=false;
end;

procedure TForm1.KenaikanTitikDidih1Click(Sender: TObject);
begin
image1.Visible:=false;
panel1.Visible:=true;
panel2.Visible:=false;
groupbox5.Visible:=false;
groupbox6.Visible:=true;
groupbox7.Visible:=false;
groupbox8.Visible:=false;
end;

procedure TForm1.PenurunanTitikBeku1Click(Sender: TObject);
begin
image1.Visible:=false;
panel1.Visible:=true;
panel2.Visible:=false;
groupbox5.Visible:=false;
groupbox6.Visible:=false;
groupbox7.Visible:=true;
groupbox8.Visible:=false;
end;

procedure TForm1.ekananOsmotik1Click(Sender: TObject);
begin
image1.Visible:=false;
panel1.Visible:=true;
panel2.Visible:=false;
groupbox5.Visible:=false;
groupbox6.Visible:=false;
groupbox7.Visible:=false;
groupbox8.Visible:=true;
end;

procedure TForm1.Home1Click(Sender: TObject);
begin
image1.Visible:=true;
panel1.Visible:=false;
panel2.Visible:=false;
end;

procedure TForm1.FormCreate(Sender: TObject);
begin
panel1.Visible:=false;
panel2.Visible:=false;
end;

procedure TForm1.Button1Click(Sender: TObject);
begin
n1:=strtofloat(edit1.Text);
v1:=strtofloat(edit2.Text);
M1:=n1/v1;
label3.Caption:='Molaritas larutan sebesar '+floattostr(M1)+' mol/L';
end;

procedure TForm1.Button2Click(Sender: TObject);
begin
massa2:=strtofloat(edit3.Text);
Mr2:=strtofloat(edit4.Text);
v2:=strtofloat(edit5.Text);
M2:=(massa2/Mr2)*(1000/v2);
label7.Caption:='Molaritas larutan sebesar '+floattostr(M2)+' mol/L';
end;

procedure TForm1.Button3Click(Sender: TObject);
begin
massa3:=strtofloat(edit6.Text);
Mr3:=strtofloat(edit7.Text);
mp3:=strtofloat(edit8.Text);
Molal3:=(massa3/Mr3)*(1000/mp3);
label11.Caption:='Molalitas larutan sebesar '+floattostr(Molal3)+' mol/kg';
end;

procedure TForm1.Button4Click(Sender: TObject);
begin
nt4:=strtofloat(edit9.Text);
np4:=strtofloat(edit10.Text);
xt4:=nt4/(nt4+np4);
xp4:=np4/(nt4+np4);
label14.Caption:='Fraksi mol zat terlarut sebesar '+floattostr(xt4);
label15.Caption:='Fraksi mol pelarut sebesar '+floattostr(xp4);
end;

procedure TForm1.Button5Click(Sender: TObject);
begin
po5:=strtofloat(edit11.Text);
xt5:=strtofloat(edit12.Text);
dp5:=po5*xt5;
label18.Caption:='Penurunan tekanan uap jenuh larutan sebesar '+floattostr(dp5);
end;

procedure TForm1.Button6Click(Sender: TObject);
begin
kb6:=strtofloat(edit13.Text);
massa6:=strtofloat(edit14.Text);
Mr6:=strtofloat(edit15.Text);
mp6:=strtofloat(edit16.Text);
dt6:=kb6*(massa6/Mr6)*(1000/mp6);
label23.Caption:='Kenaikan titik didih larutan sebesar '+floattostr(dt6)+' C';
end;

procedure TForm1.Button7Click(Sender: TObject);
begin
kf7:=strtofloat(edit17.Text);
massa7:=strtofloat(edit18.Text);
Mr7:=strtofloat(edit19.Text);
mp7:=strtofloat(edit20.Text);
dt7:=kf7*(massa7/Mr7)*(1000/mp7);
label28.Caption:='Penurunan titik beku larutan sebesar '+floattostr(dt7)+' C';
end;

procedure TForm1.Button8Click(Sender: TObject);
begin
M8:=strtofloat(edit21.Text);
T8:=strtofloat(edit22.Text);
phi8:=M8*R*T8;
label31.Caption:='Tekanan osmotik larutan sebesar '+floattostr(phi8)+' atm';
end;

end.
